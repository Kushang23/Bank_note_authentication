The dataset used for this project is “banknote authentication Data Set”, which is sourced at UCI ML (https://archive.ics.uci.edu/ml/datasets/banknote+authentication). The data set is gathered by extracting data from the images of real and fake bank notes. The images were collected using an industrial camera with final images of resolution (400 x 400) pixels. The following attributes were extracted from the images, forming the dataset.
1. Variance of Wavelet Transformed image (continuous)
2. Skewness of Wavelet Transformed image (continuous)
3. Curtosis of Wavelet Transformed image (continuous)
4. Entropy of image (continuous)
5. Class (integer)
The dataset contains 4 attributes and a single target variable. The target value is denoted by 1 (if real) and 0 (if fake). The note is classifiedd based on the 4 attributes.
In total there are 1372 data points. 75% will be used to train and the rest will be tested.
Data Set Characteristics: Multivariate
Number of Instances: 1372 
Area:Computer
Attribute Characteristics: Real
Number of Attributes:5 
Date Donated:2013-04-16 
Associated Tasks:Classification
Missing Values? N/A
Number of Web Hits:392377

Dataset Description (https://archive.ics.uci.edu/ml/datasets/banknote+authentication)
We standardize the dataset by setting the mean as zero and standard deviation as one for each attribute. We had to apply 3 classification models to the dataset. We decided to go with AdaBoost, Naïve Bayes and K Nearest Neighbors for the classification.
