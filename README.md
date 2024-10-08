Mall Customers Segmentation
Project Overview
This Jupyter notebook performs customer segmentation analysis based on the demographic and spending data of mall customers. It uses K-Means clustering to identify different segments of customers and visualize the results. The main objective is to understand the patterns in customer behavior and group customers based on their similarity for potential business insights.

Key Features
Data Preparation: The notebook reads customer data and processes it for analysis.
Clustering with K-Means: Utilizes the K-Means clustering algorithm to group customers into distinct segments.
Silhouette Analysis: Evaluates the quality of clusters using silhouette scores.
3D Visualization: Employs 3D scatter plots for enhanced visualization of clusters using plotly.
Seaborn and Matplotlib Visualizations: Provides various 2D plots for understanding the data distribution and cluster formations.
Libraries Used
The notebook utilizes the following Python libraries:

pandas: For data manipulation and handling.
matplotlib: For basic data visualization.
seaborn: For enhanced and aesthetically pleasing plots.
sklearn: For implementing the K-Means clustering algorithm and evaluating its performance.
plotly: For interactive 3D visualizations of the customer segments.
Usage
To run the notebook:

Ensure you have Python installed with the required libraries.
You can install the necessary libraries via pip:
bash
Kopiera kod
pip install pandas matplotlib seaborn scikit-learn plotly
Open the notebook in Jupyter and run the cells to execute the analysis.
Data
The dataset used in this notebook contains mall customers' demographic and spending data. The dataset includes features such as:

Age: Customer's age.
Annual Income: Annual income of the customer in thousand dollars.
Spending Score: A score assigned by the mall based on customer spending behavior.
Clustering Process
Data Exploration: The notebook begins by loading and exploring the dataset to understand its structure.
Feature Selection: Relevant features such as Age, Income, and Spending Score are selected for clustering.
K-Means Clustering: The K-Means algorithm is applied with varying cluster numbers to determine the optimal segmentation.
Cluster Evaluation: The silhouette score is computed to assess the quality of the clustering.
Visualization: The final clusters are visualized using 2D and 3D scatter plots for easy interpretation.
