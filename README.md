# MGCN-Code

This repository contains the official implementation of the MGCN (Multi-hop Graph Convolutional Network) model used in our study evaluating performance on three benchmark citation datasets: **Cora**, **CiteSeer**, and **PubMed**.

## 📁 Files Included
- `MGCN_notebook.ipynb`: Main notebook with model training and evaluation
- `requirements.txt`: Required packages and dataset source info
- (Optional) Additional helper scripts or logs

## 📊 Datasets
We use datasets from the `torch_geometric.datasets.Planetoid` class:
- [Cora](https://github.com/kimiyoung/planetoid/raw/master/data)
- [CiteSeer](https://github.com/kimiyoung/planetoid/raw/master/data)
- [PubMed](https://github.com/kimiyoung/planetoid/raw/master/data)

These datasets are **automatically downloaded** and **preprocessed** by PyTorch Geometric.

## 🚀 How to Run
```bash
pip install -r requirements.txt
# Open the notebook and run cells step-by-step
