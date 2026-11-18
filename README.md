# DSC212Assignment
# Modularity in the Karate Club Graph

## Overview
This project explores community detection in Zachary's Karate Club network using **Spectral Modularity Maximization**. It uses eigenvalues and eigenvectors of the modularity matrix to identify groups of closely connected nodes.

## Objectives
- Construct the Karate Club graph using NetworkX.
- Calculate the adjacency and modularity matrices.
- Apply recursive spectral partitioning to detect communities.
- Visualize community divisions after each iteration.
- Analyze degree, betweenness, closeness centrality and clustering coefficient.

## How to Run
1. Open the `DSC212_Assignment.ipynb` notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries:

   ```bash
   pip install networkx numpy matplotlib
   ```
3. Run all cells to execute the algorithm and generate visualizations.

## References
1. Newman, M. E. J. (2006). *Modularity and community structure in networks*. Proceedings of the National Academy of Sciences, 103(23), 8577–8582.
2. Zachary, W. W. (1977). *An information flow model for conflict and fission in small groups*. Journal of Anthropological Research, 33, 452–473.

## Conclusion
The project demonstrates how spectral methods can identify communities in social networks and how network metrics help analyze the structural importance of individual nodes.
