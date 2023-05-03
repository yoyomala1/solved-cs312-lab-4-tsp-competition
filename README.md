Download Link: https://assignmentchef.com/product/solved-cs312-lab-4-tsp-competition
<br>
<span class="kksr-muted">Rate this product</span>

TSP Competition

TSP Problem Description: ​Given a set of cities (coordinates) and distances between them, find the best (shortest) tour (visiting all cities exactly once and returning to the origin city) in a given amount of time, viz. ​Travelling Salesman Problem​.

Note: ​You are free to implement any algorithm for this competition. Input Format:You will be given files in the following format:

● ​First line will contain either ​​euclidean ​o​ r ​non euclidean​ indicating whether the distances between the cities are Euclidean or not.

<ul>

 <li>●​  ​Second line will contain the number of cities (​​N​​). E.g. 100 (Indices 0 – 99)</li>

 <li>●​  ​Next ​​N​​ lines will contain the two-dimensional coordinates (space separated) of the cities.</li>

 <li>●​  ​Next​​N​​lineswillcontain​​N​​spaceseparateddistancesbetweencities,inorder.</li>

 <li>●​  ​All coordinates and distances will be floating point numbers.Sample input files have been attached on moodle.​Output Format:Your output should be following:</li>

</ul>

● ​Each line will contain tours as space separated indices of cities. Do not write the origin city’s index at last again. Rotated tours will be considered the same. Invalid tours will be considered as no tours at all.

● ​The ​time limit ​for running your code is 300s​, after which your process will be terminated. Make sure to print your best tours to stdout as soon as you find them because only the last valid tour will be considered for evaluation. And also print the tour length in each round.

●​ ​Do not use multi-threading​ for this assignment.

Submission format:

You need to submit the following: ● ​Code

● ● ●

​Script to run your code called run.sh which accepts an input file name as argument Readme.txt ( How to execute your file)A brief report stating your methodology and iterative improvements. (​​report.pdf​​)

Submit a zip with your groupID as the name: eg. 1.zip

Evaluation

​● You will be evaluated on the basis of the cost of your tours.​● Refer to test cases from the previous assignment(trial) so that you can evaluate your

performance and improve before the final submission.​● ​Judgment will be made in a relative fashion with some thresholding.​● We are also attaching results from previous batches so that you can compare your results. ​● The maximum points are 100.

​Evaluation Criteria: ​Relative (based on tour found)