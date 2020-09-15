# BMI-Lab3
Libraries needed:
1. Pandas
2. Numpy

Usage:

Use different py file according to the dataset you are testing, because the preprocessing step is different

The program should be executable with at least 3 parameters: the name of the dataset file, k, and the name of the output file. For example, to run the program with iris.data.txt, 3 clusters and ‘outputFile’: 

    python kMeansClustering.py water-treatment.data 3 outputFile

Output:
The file contains numerical class labels (formatted as one number per row) for all the records in the test dataset and the sum squared error (SSE) and silhouette coefficient in the last row.