# Project 10 - Using unsupervised machine learning techniques like K-Means and Principal Component Analysis techniques to cluster or segment cryptocurrency data.

---

## Technologies

Technologies used to complete this project include:

a) Programming Language: Python version 3.9.12 (this application will be stable for Python versions 3.7 and above)

b) Libraries and frameworks: I used following Python libraries and frameworks to complete this project
 - Pandas
 - pathlib, specifically the Path() function
 - hvplot
 - Scikit-Learn
 - warnings

c) Operating Systems: This application was created in Windows 10.

---

## Installation Guide

Before running the application, first import the following libraries:
    
    Import required libraries and dependencies
    import pandas as pd
    import hvplot.pandas
    from pathlib import Path
    from sklearn.cluster import KMeans
    from sklearn.decomposition import PCA
    from sklearn.preprocessing import StandardScaler
    import warnings
    warnings.filterwarnings('ignore')

Also ensure that the visual plots are displayed within the Jupyter Notebook using the code:
    %matplotlib inline

---

## Usage

1) We start by taking crytocurrency data. We have these data in a CSV file from which we'll import the data to Pandas dataframe. We generate basic summary statistics of the data and perform visual exploratory analysis. 

2) We then go to the next phase. We prepare the data by Standardizing it, i.e, by subtracting the variable's mean from each data point and subtracting this difference by the standard deviation. Standardization allows us to compare variables of different magnitudes.

3) We then find the best value for the number of clusters using the Elbow Curve method. Once we have the best value for the number of clusters, we pass the data to the K-Means clustering algorithm and get the clustered output.

4) We then optimize our dataset and our clusters by applying Principal Component Analysis, which is a dimensionality reduction algorithm that linearly combine the features, condenses the features, and returns the principal components. These principal components contain the majority of information of the original dataset. By applying the PCA technique, we can significantly reduce the number of features in our dataset.

5) We repeat step # 3. We find the best value for the number of clusters using the Elbow Curve method. Once we have the best value for the number of clusters, we pass the principal components dataset (not the original dataset) to the K-Means clustering algorithm and get the clustered output.

---

## Contributors

 - Main contribution - Aanchal Khanna
 - LinkedIn Profile - https://www.linkedin.com/in/aanchal-khanna-7b126721b/

---

## License

The license used for this project is "MIT License"