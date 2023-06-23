# GraphAnalysis-ENZYMES-G295 Project

This project focuses on analyzing a graph network using various metrics and algorithms. The code is written in a Jupyter Notebook and utilizes libraries such as NetworkX, scikit-learn, matplotlib, pandas, and numpy.

## Description

The project uses different metrics to analyze a graph network. It performs the following tasks:

1. Reads a graph network from an input file using NetworkX.
2. Displays the number of edges and nodes in the graph.
3. Visualizes the graph using matplotlib, making it more readable.
4. Computes and visualizes various metrics:
   - Node Degree: Computes the degree of each node and visualizes it using a histogram.
   - Clustering Coefficient: Calculates the clustering coefficient of each node and visualizes it using a histogram.
   - Centrality Measures: Calculates different centrality measures, including degree centrality, closeness centrality, betweenness centrality, and eigenvector centrality, and visualizes them using histograms.
   - Average Shortest Path Length: Calculates the average shortest path length of the graph.
5. Detects communities within the graph:
   - Utilizes the Modularity Maximization algorithm to find communities based on the graph's structure.
   - Calculates the modularity value, which indicates the quality of the community detection.
   - Displays the number of communities found and lists the nodes within each community.
   - Visualizes the communities using different colors for each community.
6. Performs Spectral Clustering:
   - Prepares the graph for clustering analysis by removing self-loop edges and converting it to an undirected graph.
   - Uses the SpectralClustering algorithm from scikit-learn to perform clustering on the graph.
   - Visualizes the graph based on the community assignments obtained from spectral clustering.
  
## Usage

To run the code in this project, follow these steps:

1. Clone the repository to your local machine:
 ```
   git clone https://github.com/iliastzanis/GraphAnalysis-ENZYMES-G295-GR/.git
 ```
2. Navigate to the project directory:
3. Launch Jupyter Notebook:
4. Open the `graph_analysis_project.ipynb` notebook.
5. Run each cell in the notebook sequentially to execute the code.
> Note: Ensure that you have the necessary dependencies installed. You can install them using pip
6. Explore the code and modify it according to your needs.

Feel free to experiment with different graph datasets and adjust the parameters and visualizations to suit your requirements.

