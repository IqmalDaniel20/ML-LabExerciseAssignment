# K-Means Clustering Lab Enhancement

## Overview

This repository contains the enhanced version of the K-Means Clustering lab, part of the Machine Learning coursework. It includes a detailed implementation of K-Means clustering with both random initialization and K-Means++ initialization, along with advanced techniques like the Elbow method and Silhouette analysis to determine the optimal number of clusters.

## Objectives

- To demonstrate the implementation of K-Means clustering from scratch.
- To compare the effectiveness of random initialization vs. K-Means++ initialization.
- To apply techniques such as the Elbow method and Silhouette analysis to evaluate clustering performance.

## Data Description

The `Mall_Customers.csv` dataset includes information about mall customers, such as:
- Annual Income (in thousand dollars)
- Spending Score (1-100)

## Exploratory Data Analysis (EDA)

- Statistical summary and visualization of the data.
- Preprocessing steps including data scaling.

## Clustering Implementation

- **K-Means with Random Initialization**: Implementation details and cluster visualization.
- **K-Means with K-Means++ Initialization**: Enhancements over random initialization and visualization.
- **Elbow Method**: Determination of the optimal number of clusters based on inertia.
- **Silhouette Analysis**: Evaluation of clustering performance using silhouette scores.

## Results and Discussion

- Discuss the findings from different initializations and the effectiveness of evaluation metrics.
- Visualizations of clusters and interpretations of centroids.

## Conclusion

Summary of the lab findings and potential future enhancements or applications of K-Means clustering.

## Installation and Execution

To interact with the analysis and models:
1. **Open Google Colab**: Visit [Google Colab](https://colab.research.google.com/).
2. **Import the Notebook**: Click on `File` > `Upload notebook` > `Choose file` to upload the `.ipynb` file.
3. **Upload the Dataset**:
   - Navigate to the sidebar, select the `Files` tab, and click on `Upload to session storage`.
   - Drag and drop the `Mall_Customers.csv` file into the Colab session storage.
4. **Run the Notebook**: Execute the code cells sequentially to explore the analysis and model training steps.