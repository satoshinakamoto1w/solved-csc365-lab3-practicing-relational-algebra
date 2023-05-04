Download Link: https://assignmentchef.com/product/solved-csc365-lab3-practicing-relational-algebra
<br>
In this lab, you are going to practice some of the operators of relational algebra you learned in class. It is going to be a good segue to writing queries in SQL.

<strong>Preparation </strong>

Download a zip file from Polylearn. The zip file should contain ra.jar and sample.properties.

<h1>Starting Up</h1>

To start the radb tool type the following command where you placed the ra.jar and sample.properties file (you need to have Java installed on your machine):

java -jar ra.jar sample.properties

(To quit, type quit;)

The tool is written by a professor at Duke. It does not support all operations of relational algebra and I do not think some of the operators follow the standard precisely in some edge cases. However, it is a good tool for us to practice relational algebra on a database.

Read the online documentation here for usage: <u>​</u><a href="https://users.cs.duke.edu/~junyang/ra2/">https://users.cs.duke.edu/~junyang/ra2/</a>

<h1>Exercises</h1>

Write the following queries in relational algebra.

<ol>

 <li>List the relations available in the database with list command (6 relations should be available).</li>

 <li>Print all tuples in Bar.</li>

 <li>Print all tuples in Beer.</li>

 <li>Print all tuples in Drinker.</li>

 <li>Print all tuples in Frequents.</li>

 <li>Print all tuples in Serves.</li>

 <li>Print all tuples in Likes.</li>

 <li>Print all the names of bar Amy frequents.</li>

 <li>Print all the names of beer Amy likes.</li>

 <li>Print the name of the bar Ben frequents the most (do not hard code the name of the bar).</li>

 <li>Print the name(s) of a person/persons who frequents James Joyce Pub the most (Do not hard code the name of drinker).</li>

 <li>Print the name of the cheapest beer served in town and the name of the bar where it is available (Do not hard code the name of beer).</li>

 <li>Print the name of beer commonly liked by Amy, Ben, Eve, and Dan (Do not hard code the name of beer).</li>

 <li>Print the name of beer nobody likes (Do not hard code the name of beer nor the names of drinkers).</li>

</ol>

Demo your work and copy the relational algebra (2-14) you wrote to a text file and submit it to Polylearn.