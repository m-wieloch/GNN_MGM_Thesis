# Masked Graph Modeling for Node Classification and Link Prediction

This repository contains notebooks and code for exploring the application of Masked Graph Modeling (MGM) for node classification and link prediction tasks using Graph Neural Networks (GNNs). The project focuses on both real-world and synthetic datasets to evaluate different masking strategies and their impact on GNN performance.

## Repository Structure

The repository is organized into the following directories:

### 1. `RealDatasets/`

This directory contains Jupyter notebooks that implement MGM techniques on real-world datasets. The datasets include Citeseer, Cora, and PubMed. Each notebook explores different strategies for masking graph structures, such as edges and node paths, and evaluates their effect on link prediction and node classification tasks. Various architectures were utilized to assess how different models respond to the applied masking strategies.

- `Citeseer/`
  - **MGM_CiteseerEdgePathMaskNodePredClass.ipynb**: Applies strategies to the Citeseer dataset.
  - **MGM_CiteseerMaskStratCompareNodePredClass.ipynb**: Compares different masking strategies on the Citeseer dataset.

- `Cora/`
  - **MGM_CoraEdgePathMaskNodePredClass.ipynb**: Explores edge and path masking on the Cora dataset.
  - **MGM_CoraMaskStratCompareNodePredClass.ipynb**: Compares other masking strategies on the Cora dataset.

- `PubMed/`
  - **MGM_PubMedEdgePathMaskNodePredClass.ipynb**: Implements edge and path masking on the PubMed dataset.
  - **MGM_PubMedMaskStratCompareNodePredClass.ipynb**: Compares masking strategies on PubMed.

### 2. `SyntheticDatasets/`

This directory contains Jupyter notebooks that implement MGM techniques on synthetic datasets. These notebooks explore diffrent masking strategies, divergent architectures and finally compare the performance of various masking techniques.

- **MGM_SynthEdgeMaskNodePredClass.ipynb**: Applies edge masking on synthetic datasets.
- **MGM_SynthEdgePathMaskNodePredClass.ipynb**: Implements both edge and path masking on synthetic datasets.
- **MGM_SynthMaskStratCompareNodePredClass.ipynb**: Compares other  masking strategies on synthetic datasets.

### 3. `requirements.txt`

This file lists all the Python dependencies required to run the Jupyter notebooks in this repository.

## Installation

To get started, clone the repository and install the required dependencies.