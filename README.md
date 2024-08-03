# Time-Series-Clustering-on-ECG

Dataset - 
UCR Time Series Classification Archive. The UCR (University of California, Riverside) repository is a well-known and widely used collection of time series datasets. Largest public collection of 85 class-labeled time series dataset. 

Link - https://www.cs.ucr.edu/~eamonn/time_series_data/

The ECG (Electrocardiogram) dataset from the UCR Time Series Classification Archive is one of the many datasets available for benchmarking time series classification algorithms. 

### ECG Datasets in UCR Repository
There are multiple ECG-related datasets in the UCR repository, including but not limited to:

1. ECG200
2. ECG5000
3. ECGFiveDays
   
Each dataset has its own unique characteristics:

1. ECG200

Description: This dataset consists of 200 instances of ECG signals, with each signal being 96 time points long.
Classes: There are 2 classes representing different heartbeats (normal vs. abnormal).
Train/Test Split: Typically, there are 100 instances for training and 100 for testing.

2. ECG5000
Description: This dataset contains a larger set of 5000 ECG instances, each with 140 time points.
Classes: It includes 5 different classes of heartbeats.
Train/Test Split: Commonly, there are 500 instances for training and 4500 for testing.

3. ECGFiveDays
Description: This dataset includes 884 instances, each with 136 time points.
Classes: There are 2 classes representing different conditions.
Train/Test Split: Usually, there are 23 instances for training and 861 for testing.
Data Format
The datasets from the UCR repository are usually provided in two formats:

First, I am exploring ECGFiveDays. In which classification model is built using k-shape algorithm.

## K-shape Algorithm 
K-shape is state-of-the-art approach to time series clustering, which uses a distance measure that is invariant to scaling and shifting to preserve the shapes of time series sequences while comparing them. It requires minimal parameter tuning. 

Difference between k-means and k-shape is while calculating distance, k-shape uses shaped based distance that relies on cross-correlations.

