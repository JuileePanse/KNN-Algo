# KNN-Algorithm
 The k-nearest neighbors (KNN) algorithm is a simple, easy-to-implement supervised machine
 learning algorithm that can be used to solve both classification and regression problems.
 This algorithm is dependent on distance for classification, normalizing the training data can improve its accuracy dramatically.
 
<pre>
<li>It is used when: </li>
    - You have a bunch of objects that have been classified, and</li><br>
    - You want a way to automatically clasify similar objects that haven’t gotten classified.</li><br>

<li>Procedure of automation</li>
Step 1: Define similarity of two objects<br>
Step 2: Compare the similarity of a given unrated object with all the classified objects.<br>
Step 3: Take the most similar objects and call them neighbors, who each have a “label.”<br>
Step 4: Determine the "label" of the unrated object.<br>
</pre>

# Example 1
Let’s consider the simplest case of using a KNN model as a classifier. Let’s say you have data points that fall into one of three classes. A two dimensional example may look like this:

<img src="knn.png"></img>

# Example 2
<pre>
For example, movie rating:

You have a bunch of movies that have been classified as “thumbs up” or “thumbs down,”.<br>
You want to classify the movie "Toy Story"<br> 
    Step 1: Define the attributes of "Toy Story"<br>
           Length of movie<br>
           Genre<br>
           Number of Oscar-winning actors in it<br>
           Budget<br><br>
    Step 2: find the majority rating of other movies with similar attributes<br>
    Step 3: Assign rating to "Toy Story"<br><br>

If there is a majority rating, then the rating of "Toy Story" should have the same rating.
If there’s a tie, then the rating of "Toy Story" is randomlyassigned.
</pre>

# References
https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm <br>
https://towardsdatascience.com/the-basics-knn-for-classification-and-regression-c1e8a6c955
