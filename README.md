# K-Means Clustering Algorithm
Implementation in C++ of the K-Means clustering algorithm.

Examples of datasets are in datasets folder.

References are in references folder.

This link was very useful for me: http://mnemstudio.org/clustering-k-means-example-1.htm

The implementation is in the file kmeans.cpp.

Each dataset is in format expected by the program.

Explanation of the format:

First line: A B C D E

"A" is the amount of data points.<br />
"B" is the amount of attributes.<br />
"C" is the amount of clusters.<br />
"D" is the maximum iterations.<br />
"E" indicates if contains a name for each data point. The value for "E" is 0 (not contains) or 1 (contains).<br />
The next "A" lines contains "B" attributes and the data point name (if "E" variable is 1).<br />

Example of dataset:

7 2 2 100 0<br />
1.0 1.0<br />
1.5 2.0<br />
3.0 4.0<br />
5.0 7.0<br />
3.5 5.0<br />
4.5 5.0<br />
3.5 4.5<br />

7 is the amount of data points.<br />
2 is the amount of attributes.<br />
2 is the amount of clusters.<br />
100 is the maximum iterations.<br />
0 indicates that not contains data point name.<br />
The next 7 lines contains 2 attributes each.<br />

Example that contains data point name (iris-data):

150 4 3 100 1<br />
5.1 3.5 1.4 0.2 Iris-setosa<br />
4.9 3.0 1.4 0.2 Iris-setosa<br />
4.7 3.2 1.3 0.2 Iris-setosa<br />
4.6 3.1 1.5 0.2 Iris-setosa<br />
(...)<br />

The euclidean distance was used for to calculate the distance of each data point for the centroid of cluster.

The algorithm stops by maximum number of iterations or if no data point exchange cluster.

Doubts? mcastrosouza@live.com
