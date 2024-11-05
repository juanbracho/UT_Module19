# UT_Module19
 
# Cryptocurrency Clustering with K-Means and PCA

This project demonstrates clustering cryptocurrencies based on their price change percentages over different time periods using K-Means, an unsupervised learning algorithm. Principal Component Analysis (PCA) is also applied to reduce dimensionality, improving the efficiency and visualization of clustering results.

## Topics Learned
* Unsupervised Learning: This project applies unsupervised learning techniques to group data without predefined labels.
* K-Means Clustering: We used K-Means to group cryptocurrencies into clusters based on their similarities.
* Principal Component Analysis (PCA): PCA was employed to reduce data dimensionality while preserving most of the information, aiding in visualization and efficiency.

### Prerequisites
- Python 3.8+
- Install the required libraries using requirements.txt.

## Setup Instructions
1. Clone this repository or download the project files.
2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
3. Open the Jupyter Notebook (e.g., Crypto_Clustering.ipynb) to follow along with the code and visualizations.

## Steps in the Notebook
1. Data Loading: Load cryptocurrency data containing price changes over various periods.
2. Data Preprocessing: Scale the data using StandardScaler to normalize values, preparing it for clustering.
3. Finding Optimal Clusters (Elbow Method):
* Calculate the inertia (within-cluster sum of squares) for a range of clusters to identify the optimal number of clusters using the Elbow method.
4. Clustering with Original Data: Use K-Means to assign clusters to the original scaled data and visualize the clusters in 2D.
5. Dimensionality Reduction with PCA: Reduce the data to three principal components using PCA to retain the most important information.
6. Finding Optimal Clusters with PCA Data: Apply the Elbow method on PCA data to identify the optimal number of clusters and re-cluster.
7. Comparing Results: Visualize and compare the clusters created using the original data versus the PCA-transformed data, analyzing the impact of dimensionality reduction on clustering.

## Running the Code

Each section in the notebook is documented with code cells. Run each cell in sequence to process and analyze the data, visualize the clustering, and compare results. The final analysis highlights the impact of dimensionality reduction on clustering.