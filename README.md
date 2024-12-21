# Iris Dataset Clustering Project

## Description
This project applies clustering techniques to the Iris dataset to group similar data points. KMeans and Hierarchical clustering methods are implemented and evaluated. The objective is to demonstrate clustering capabilities using unsupervised learning.

## Project Overview
1. **Dataset**: The Iris dataset from the sklearn library, excluding the species column to focus on clustering.  
2. **Preprocessing**:
   - Removed the species column since clustering is unsupervised.
   - Standardized the dataset for optimal clustering results.  
3. **Clustering Algorithms**:
   - **KMeans Clustering**:
     - Groups data into clusters by minimizing intra-cluster variance.
     - Suitable for Iris due to its structured, numerical data.
     - Visualized clusters using scatter plots.
   - **Hierarchical Clustering**:
     - Builds a hierarchy of clusters using an agglomerative approach.
     - Suitable for Iris as it identifies hierarchical relationships.
     - Visualized using dendrograms and scatter plots.  
4. **Visualization**:
   - Scatter plots and dendrograms were used to interpret the clusters effectively.  

## Insights
- **KMeans Clustering**:
  - Successfully grouped data into three clusters, aligning closely with the actual species.
  - Quick and efficient for structured data like Iris.  
- **Hierarchical Clustering**:
  - Revealed hierarchical relationships between data points.
  - Dendrograms provided deeper insights into cluster formation.  
- Both methods demonstrated the natural clustering tendency in the Iris dataset.  
- KMeans proved faster, while Hierarchical clustering offered rich interpretability.

## Conclusion
The Iris dataset showcases the utility of clustering algorithms in discovering patterns and natural groupings. KMeans and Hierarchical clustering effectively demonstrated their strengths, with each method excelling in different aspects of the analysis.

## Requirements
- Python 3.x  
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`, `scipy`

## Instructions
1. Clone this repository.  
2. Open the Jupyter Notebook file.  
3. Run the cells sequentially to preprocess data, apply clustering algorithms, and visualize results.

## Acknowledgments
- Dataset: sklearn library's Iris dataset.  
- Tools: Python and Jupyter Notebook.
