# Influential Node Analysis in Social Networks

This repository provides a Jupyter Notebook for analyzing the most influential nodes in a social network using graph theory and diffusion models. The notebook demonstrates how to load, process, analyze, and visualize a directed network, with a focus on identifying central nodes and simulating information spread.

## Features

- **Graph Construction**: Reads node and edge data from CSV files and constructs a directed graph using NetworkX.
- **Node Attribute Analysis**: Visualizes and explores node attributes, including centrality measures (degree, closeness, betweenness).
- **Community and Influence Detection**: Implements functions to identify key nodes by label, modularity class, and top measures. Finds reference and bridge nodes in the network.
- **Distribution Visualization**: Plots histograms to show the distribution of top 100 nodes according to various centrality metrics.
- **Graph Visualization**: Provides functions for drawing graphs with active/inactive nodes and custom layouts.
- **Diffusion Simulation**: Simulates the spread of influence or information through the network from a given start node, optionally visualizing the process over multiple iterations.

## File Structure

- `diffusion_models.ipynb`: Main analysis notebook with code, explanations, and visualizations.
- `graph_data/jalili_nodes.csv`: CSV file containing node information (attributes, centrality metrics, etc.).
- `graph_data/jalili_edges.csv`: CSV file containing edge information (source, target, weight, etc.).

## Requirements

- Python 3.x
- Jupyter Notebook
- NetworkX
- Pandas
- NumPy
- Matplotlib

Install dependencies using:

```bash
pip install networkx pandas numpy matplotlib
```

## Getting Started

1. **Clone the repository**:

    ```bash
    git clone https://github.com/FaSha20/Finding-the-Most-Influential-Nodes-in-Social-Network.git
    cd Finding-the-Most-Influential-Nodes-in-Social-Network
    ```

2. **Ensure data files are present**:

    - Place `jalili_nodes.csv` and `jalili_edges.csv` inside the `graph_data/` directory.

3. **Run the Jupyter Notebook**:

    ```bash
    jupyter notebook diffusion_models.ipynb
    ```

4. **Follow the sections**:

    - Data loading and graph building
    - Centrality analysis and top node finding
    - Visualization of distributions and graphs
    - Diffusion simulation

## Usage

- Change the input CSV files as needed to use your own social network data.
- Modify simulation parameters (such as start node, number of iterations, or disabled nodes) in the notebook cells.
- Use provided functions to analyze communities, influential nodes, and simulate different diffusion scenarios.

## Example Visualizations

- Histograms of top 100 nodes by closeness, degree, and betweenness centrality.
- Animated or static visualizations showing activation of nodes during diffusion.

## Notes

- Some comments and outputs in the notebook are in Persian (Farsi). The code and logic are universally applicable.
- The notebook is intended as a starting point for analyzing complex networks and can be extended with more advanced diffusion models or community detection algorithms.

## License

MIT License

## Author

[FaSha20](https://github.com/FaSha20)
