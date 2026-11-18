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

## Technologies Used
- Python
- NumPy
- NetworkX
- Matplotlib

## How to Run
1. Open the `.ipynb` notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries:

   ```bash
   pip install networkx numpy matplotlib
   ```
3. Run all cells to execute the algorithm and generate visualizations.

## References
1. Newman, M. E. J. (2006). *Modularity and community structure in networks*. Proceedings of the National Academy of Sciences, 103(23), 8577–8582. [Read paper](https://doi.org/10.1073/pnas.0601602103)
2. Zachary, W. W. (1977). *An information flow model for conflict and fission in small groups*. Journal of Anthropological Research, 33, 452–473.
3. [NetworkX – Karate Club Graph Documentation](https://networkx.org/documentation/stable/reference/generated/networkx.generators.social.karate_club_graph.html)
4. [NumPy – Linear Algebra Documentation](https://numpy.org/doc/stable/reference/routines.linalg.html)

## Conclusion
The project demonstrates how spectral methods can identify communities in social networks and how network metrics help analyze the structural importance of individual nodes.
