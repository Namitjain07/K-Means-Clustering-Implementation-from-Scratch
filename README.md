# K-Means Clustering Implementation from Scratch

This repository contains a Python implementation of the K-Means clustering algorithm from scratch, developed in a Jupyter Notebook. The implementation avoids using high-level machine learning libraries, providing an educational perspective on how the algorithm works under the hood.

## Features

- Custom implementation of K-Means clustering
- Data generation for clustering demonstration
- Visualization of clustering results
- Configurable number of clusters and iterations

## Prerequisites

Before running the notebook, ensure you have the following Python libraries installed:

- `numpy`: For numerical computations
- `matplotlib`: For data visualization

You can install the required libraries using:

```bash
pip install numpy matplotlib
```

## Usage

1. Clone the repository and open the Jupyter Notebook:

```bash
git clone <repository-url>
cd <repository-folder>
jupyter notebook code_K-Means.ipynb
```

2. Run the notebook cell by cell to:
   - Generate synthetic data for clustering.
   - Execute the K-Means algorithm.
   - Visualize the results of clustering.

## Implementation Details

### Steps of the Algorithm

1. **Initialization**:
   - Randomly select initial centroids from the dataset.

2. **Assignment Step**:
   - Assign each data point to the nearest centroid.

3. **Update Step**:
   - Calculate new centroids as the mean of the points assigned to each cluster.

4. **Iteration**:
   - Repeat the assignment and update steps until convergence or a maximum number of iterations is reached.

### Output

- Final cluster centroids
- Cluster assignments for each data point
- Visual representation of the clustering results

## Example

Below is an example of running the notebook:

1. **Input Data**:
   - Randomly generated data points distributed across a 2D space.

2. **Parameters**:
   - Number of clusters: `k=3`
   - Maximum iterations: `100`

3. **Output**:
   - Scatter plot of the clustered data, with centroids marked.

## Customization

You can modify the following parameters in the notebook:

- `k`: Number of clusters
- `max_iterations`: Maximum number of iterations to run the algorithm
- `tolerance`: Convergence threshold for centroid changes

## License

This project is open-source and available under the MIT License.

## Acknowledgments

This implementation is inspired by the foundational concepts of K-Means clustering in machine learning and serves as an educational tool for understanding clustering algorithms.

