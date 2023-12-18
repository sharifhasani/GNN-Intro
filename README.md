# Graph Neural Network (GNN) Introduction with PyTorch

## Overview
This Jupyter Notebook provides a step-by-step introduction to Graph Neural Networks (GNNs) using Python. It covers creating an initial graph with NetworkX, building a simple Graph Convolutional Network (GCN) for the Planetoid dataset, training the model for 100 epochs, and visualizing the training results.

## Requirements
- Python 3.8 or above
- NetworkX
- PyTorch
- Planetoid dataset

## Installation
Install the required dependencies using the following commands:
```bash
pip install networkx torch
```

Download the Planetoid dataset from [here](https://github.com/kimiyoung/planetoid/raw/master/data/ind.citeseer.x) and place it in the `data` directory.

## Contents
1. **Initial Graph Creation**
    - Use NetworkX to create an initial graph for demonstration purposes.

2. **Graph Convolutional Network (GCN)**
    - Implement a simple GCN using PyTorch.

3. **Loading Planetoid Dataset**
    - Load the Planetoid dataset and preprocess it for training.

4. **Model Training**
    - Train the GCN model on the Planetoid dataset for 100 epochs.

5. **Visualization of Training Results**
    - Visualize the training results, such as loss and accuracy, over the 100 epochs.

## Usage
1. Open the Jupyter Notebook (`gnn.ipynb` file)

2. Execute each cell in order to run the code and observe the results.

## Acknowledgements
- [NetworkX](https://networkx.github.io/) for graph creation.
- [PyTorch](https://pytorch.org/) for building and training the GCN model.
- [Planetoid dataset](https://github.com/kimiyoung/planetoid) for a sample graph dataset.

Feel free to modify and extend the notebook to explore more advanced concepts and datasets.
