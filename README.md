# MovieLens Recommendation System

![GitHub](https://img.shields.io/github/license/Ilia-Abolhasani/movielens-recommendation-system)
![GitHub](https://img.shields.io/github/stars/Ilia-Abolhasani/movielens-recommendation-system?style=social)
![GitHub](https://img.shields.io/github/forks/Ilia-Abolhasani/movielens-recommendation-system?style=social)

This repository contains a Jupyter Notebook (Code.ipynb) for a MovieLens recommendation system using dimension reduction and clustering algorithms. The system utilizes a dataset with 100,000 MovieLens ratings.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Dimension Reduction](#dimension-reduction)
- [Clustering Algorithms](#clustering-algorithms)
- [Results](#results)
- [License](#license)

## Prerequisites
Before you begin, ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Required libraries (NumPy, Pandas, Matplotlib, Scikit-learn, sklearn-som, beecolpy)

## Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Ilia-Abolhasani/movielens-recommendation-system.git
   ```
Navigate to the project directory:
   ```bash
   cd movielens-recommendation-system
   ```
Open the Jupyter Notebook Code.ipynb in your Jupyter environment.

## Usage
Follow the steps provided in the Jupyter Notebook to execute the recommendation system.

## Dimension Reduction
In the notebook, you will find PCA (Principal Component Analysis) used for dimension reduction.

## Clustering Algorithms
The following clustering algorithms are implemented and evaluated:

- Hierarchical Clustering
- K-Means
- PCA K-Means
- Self-Organizing Maps (SOM)
- PCA SOM
- Genetic Algorithm (GA) K-Means
- PCA GA K-Means
- Artificial Bee Colony (ABC) K-Means
- Ant Colony Optimization (ACO) K-Means

## Results
The notebook displays confusion matrices for each clustering algorithm and visualizes the process cost function in a figure.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

