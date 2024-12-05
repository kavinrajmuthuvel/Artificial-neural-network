Project Title
Clustering Analysis for Illness Data

Short Description
This project utilizes clustering techniques to analyze and group illness data. Using the KMeans algorithm and Silhouette analysis, the project identifies optimal clusters for improved data interpretation.

Getting Started
These instructions will guide you on how to replicate the clustering analysis using the provided dataset.

Prerequisites
Python 3.7 or later
Libraries: pandas, numpy, matplotlib, sklearn (scikit-learn)

Installing
Clone the repository or download the project files.
Install the required libraries using pip:
bash

pip install pandas numpy matplotlib scikit-learn
Running the Tests
Breakdown of Tests

Dataset Loading: 
Reads the illnessstudy.csv file and displays the first five rows.

Data Preparation:
Drops the Diagnosis column.
Scales features using StandardScaler.
Cluster Evaluation:

Computes WCSS for cluster sizes from 1 to 9.
Identifies the optimal cluster size using the elbow method.
Computes silhouette coefficients to confirm cluster quality.

Final Clustering:
Applies KMeans clustering with the optimal number of clusters.
Adds a new column, New Cluster, to the dataset with cluster labels.

Deployment:
Fit the KMeans model to the dataset.
Generate scatter plots to visualize clusters and centroids.
Save the updated dataset and visualization outputs for further analysis.
Author
Kavinraj Muthuvel

License
This project is licensed under the MIT License.

Acknowledgement
Special thanks to the Introduction to Data Analytics course Professor.