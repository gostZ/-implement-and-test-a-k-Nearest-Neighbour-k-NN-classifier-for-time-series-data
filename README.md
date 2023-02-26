# Implement-and-test-a-k-NN-classifier-for-time-series-data
## Task 1: 1-NN DTW
1.	Use the DTW function in the notebook to implement a simple 1-NN classifier for time-series data. 
2.	Test the performance of this classifier on the dataset provided in the file UMD_TEST.txt. This is a three-class synthetic time-series dataset - see details <here>.
3.	Given that the time-series are all the same length (150 ticks) Euclidean distance can also be used as distance metric. Compare the 1-NN DTW performance with 1-NN Euclidean. Use the scikit-learn implementation for the Euclidean model.  
4.	Find the best value for the window parameter for this dataset.
## Task 2: k-NN DTW
1.	The k-NN classifier in scikit-learn has a metric parameter that allows for user-defined distance metrics. Adapt the DTW code provided so that it can be incorporated  in a scikit-learn k-NN  classifier. 
2.	Test the performance of this classifier and compare with the 1-NN results from Task 1. Verify that the 1-NN results are consistent. 
3.	Compare with k-NN Euclidean. 
