# Scaling Laws in Graph Neural Networks (GNNs)

This repository explores the scaling laws in Graph Neural Networks (GNNs) through a comprehensive series of experiments and analyses. It includes preprocessing steps, scaling experiments, baseline and advanced model implementations, and detailed visualizations of performance metrics. The goal is to provide insights into GNN scalability and performance optimization across diverse datasets.

## Table of Contents
- [Overview](#overview)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Notebooks Overview](#notebooks-overview)
- [Usage](#usage)
- [Acknowledgments](#acknowledgments)
- [Contributing](#contributing)
- [License](#license)

## Overview

Graph Neural Networks (GNNs) are powerful tools for modeling graph-structured data, but their scalability with increasing layers, parameters, and data complexity is not well understood. This project investigates the following aspects:

- How GNNs scale with layers and parameters
- Performance comparison between baseline and advanced GNN architectures
- Visualization of trends and insights from experimental data

## Repository Structure

```plaintext
Scaling-Laws-in-Graph-Neural-Networks/
├── Advanced_Model_Implementation.ipynb              # Notebook for advanced GNN models
├── Baseline_Model_Implementation.ipynb              # Notebook for baseline GNN models
├── Performance_Charts_of_Advanced_Models.ipynb      # Performance analysis of advanced models
├── Performance_Charts_of_GCN.ipynb                 # Performance analysis of GCN models
├── Preprocessing.ipynb                              # Data preprocessing notebook
├── Scaling_Experiments.ipynb                        # Scaling experiments notebook
├── Visualization_of_Scaling_Experiments.ipynb       # Visualization notebook
├── LICENSE                                          # License file (MIT)
├── README.md                                        # Project README file
```

## Getting Started

### Clone the Repository

To get started, clone this repository to your local machine:

```bash
git clone https://github.com/AYMANE-JOUHARI/Scaling-Laws-in-Graph-Neural-Networks.git
cd Scaling-Laws-in-Graph-Neural-Networks
```

### Install Dependencies

Ensure you have all required libraries installed. You can install them using:

```bash
pip install -r requirements.txt
```

## Dependencies

The project requires the following Python libraries:

- numpy
- pandas
- matplotlib
- seaborn
- networkx
- torch
- torch-geometric
- scikit-learn
- jupyter

You can install these libraries individually or using a requirements.txt file.

## Notebooks Overview

### Preprocessing.ipynb
- Prepares datasets for scaling experiments and ensures data consistency

### Scaling_Experiments.ipynb
- Conducts scaling experiments by varying layers and parameters in GNNs
- Tests on different datasets to observe trends

### Visualization_of_Scaling_Experiments.ipynb
- Creates visualizations of results from the scaling experiments
- Provides insights into GNN performance

### Baseline_Model_Implementation.ipynb
- Implements standard GNN models such as GCNs for benchmarking

### Advanced_Model_Implementation.ipynb
- Explores more advanced GNN architectures with improved scalability and performance

### Performance_Charts_of_GCN.ipynb
- Analyzes and visualizes performance metrics for GCN models

### Performance_Charts_of_Advanced_Models.ipynb
- Compares advanced GNN models to the baseline in terms of performance and scalability

## Usage

1. **Run Preprocessing:**
   - Start by running the `Preprocessing.ipynb` notebook to prepare the datasets

2. **Scaling Experiments:**
   - Use `Scaling_Experiments.ipynb` to perform the scaling experiments

3. **Visualize Results:**
   - Run `Visualization_of_Scaling_Experiments.ipynb` to generate graphs and insights

4. **Baseline and Advanced Models:**
   - Explore `Baseline_Model_Implementation.ipynb` and `Advanced_Model_Implementation.ipynb` for model implementation and evaluation

## Acknowledgments

We would like to thank the following individuals and groups for their contributions and support:

**Team Members:**
- Mouad Benchekroun mhamdi: Preprocessing and Data Preparation
- Ali Benchrifa: Baseline Model Implementation
- Marouane Benbrahim: Advanced Models
- Aymane Jouhari: Scaling, Results Visualization, and Analysis

**Advisor:**
- Dr. Zhiqian Chen

**Additional Contributions:**
- The contributors and researchers who inspired this work
- The open-source community for providing excellent tools and frameworks


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
