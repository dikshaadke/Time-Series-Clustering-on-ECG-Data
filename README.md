# Time-Series-Clustering-on-ECG

Dataset - 
UCR Time Series Classification Archive. The UCR (University of California, Riverside) repository is a well-known and widely used collection of time series datasets. Largest public collection of 85 class-labeled time series dataset. Here, I am particularly using the ECG (Electrocardiogram) dataset from the UCR Time Series Classification Archive is one of the many datasets available for benchmarking time series classification algorithms.

Link - https://www.cs.ucr.edu/~eamonn/time_series_data/

### ECG Datasets in UCR Repository
There are multiple ECG-related datasets in the UCR repository, including but not limited to:

1. ECG200 - Consist of 200 instances of ECG signals, with each signal being 96 time points long. There are 2 classes representing different heartbeats (normal vs. abnormal). Typically, there are 100 instances for training and 100 for testing.
   
2. ECG5000 - This dataset contains a larger set of 5000 ECG instances, each with 140 time points. It includes 5 different classes of heartbeats. Commonly, there are 500 instances for training and 4500 for testing.

3. ECGFiveDays - This dataset includes 884 instances, each with 136 time points. There are 2 classes representing different conditions. Usually, there are 23 instances for training and 861 for testing.

I am exploring ECGFiveDays using k-shape algorithm and ECG5000 datasets using k-shape, k-means and HDBSCAN algorithm. 

## K-shape Algorithm 
K-shape is state-of-the-art approach to time series clustering, which uses a distance measure that is invariant to scaling and shifting to preserve the shapes of time series sequences while comparing them. It requires minimal parameter tuning. 

Difference between k-means and k-shape is while calculating distance, k-shape uses shaped based distance that relies on cross-correlations.

