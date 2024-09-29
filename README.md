# Solubility Prediction Tool

A solubility prediction tool that utilizes Graph Neural Networks (GNNs) to predict the solubility of given molecules represented in the form of SMILES.

## Features

- Predicts the solubility of molecules based on their SMILES representation.
- Utilizes Graph Neural Networks for effective solubility predictions.
- Supports various molecular structures and provides reliable results.
- Easy integration with cheminformatics tools for enhanced analysis.

## Technologies Used

- **PyTorch**: A deep learning framework for building and training models.
- **RDKit**: A collection of cheminformatics and machine learning tools for handling chemical data.
- **PyG (PyTorch Geometric)**: A library for deep learning on irregularly structured data, specifically graph data.

## Model Description

The Solubility Prediction Tool employs a Graph Neural Network (GNN) to predict the solubility of molecules. The model processes molecular data represented in the SMILES format, leveraging the following features:

- **Input Representation**: The model takes a molecule's SMILES string as input, which is then converted into a graph structure that captures the molecular topology.
- **Graph Neural Network Architecture**: The GNN processes the graph representation to learn the relationships between atoms and their connections, enabling the model to understand the molecular structure effectively.
- **Prediction Output**: After training on a dataset of known solubility values, the model outputs the predicted solubility for the input molecule.

## Installation

Follow these steps to install and set up the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/Akkki28/Solubility-prediction.git
