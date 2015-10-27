# K-Means Clustering Algorithm
Implementation in C++ of the K-Means clustering algorithm.

Examples of datasets are in datasets folder.

References are in references folder.

This link was very useful for me: http://mnemstudio.org/clustering-k-means-example-1.htm

The implementation is in the file kmeans.cpp.

Each dataset is in format expected by the program.

Explanation of the format:

First line: A B C D
"A" is the amount of data points.
"B" is the amount of attributes.
"C" is the maximum iterations.
"D" indicates if contains a name for each data point. The value for "D" is 0 (not contains) or 1 (contains).
The next "A" lines contains "B" attributes and the data point name (if "D" variable is 1).

Example of the dataset:

7 2 2 100 0
1.0 1.0
1.5 2.0
3.0 4.0
5.0 7.0
3.5 5.0
4.5 5.0
3.5 4.5

7 is the amount of data points.
2 is the amount of attributes.
100 is the maximum iterations.
0 indicates that not contains data point name.
The next 7 lines contains 2 attributes each.

Example that contains data point name (iris-data):

150 4 3 100 1
5.1 3.5 1.4 0.2 Iris-setosa
4.9 3.0 1.4 0.2 Iris-setosa
4.7 3.2 1.3 0.2 Iris-setosa
4.6 3.1 1.5 0.2 Iris-setosa
(...)

Doubts? mcastrosouza@live.com
