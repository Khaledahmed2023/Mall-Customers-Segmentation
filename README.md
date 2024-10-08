# Mall Customers Segmentation

This repository contains a Jupyter notebook that performs customer segmentation using K-Means clustering on mall customer data. The project analyzes demographic and spending patterns, with visualization using 2D and 3D plots for better insights into customer behavior.

## Project Overview

The goal of this project is to group mall customers into distinct segments based on their similarity using the K-Means clustering algorithm. These segments provide insights into customer behavior, which can be used for targeted marketing strategies.

## Key Features

- **Data Loading and Exploration**: Reading and understanding the structure of customer data.
- **Clustering with K-Means**: Grouping customers into clusters based on demographic and spending features.
- **Cluster Evaluation**: Using silhouette scores to assess the quality of clustering.
- **Visualization**: Displaying 2D and 3D scatter plots of the clusters for intuitive analysis.

## Libraries Used

The following Python libraries are used in the notebook:

- `pandas`: Data manipulation and analysis.
- `matplotlib`: Basic data visualization.
- `seaborn`: Enhanced and aesthetically pleasing statistical plots.
- `sklearn`: K-Means clustering algorithm and silhouette score for cluster evaluation.
- `plotly`: Interactive 3D visualizations for an in-depth view of customer segments.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/repository-name.git
   ```
2. Install the required dependencies:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn plotly
   ```
3. Open the Jupyter notebook and run the cells to execute the analysis.

## Data

The dataset includes the following key features:
- **Age**: Age of the customer.
- **Annual Income**: Annual income of the customer (in thousands of dollars).
- **Spending Score**: A score assigned by the mall, reflecting customer spending behavior.

## Clustering Process

1. **Data Preparation**: Clean and preprocess the data for analysis.
2. **Feature Selection**: Use key demographic and spending features for clustering.
3. **K-Means Clustering**: Apply the K-Means algorithm with different cluster numbers to identify optimal segments.
4. **Evaluation**: Use silhouette scores to determine the best number of clusters.
5. **Visualization**: Use 2D and 3D plots to visualize the clusters and analyze customer segments.
