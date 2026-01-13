# Link Prediction using Graph Convolutional Networks (GCN)

![Project Status](https://img.shields.io/badge/status-complete-green)
![Python](https://img.shields.io/badge/python-3.x-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Geometric-orange)

## 📌 Executive Summary
This project implements a **Graph Convolutional Network (GCN)** to predict missing connections in a social network graph. By leveraging the structural properties of nodes, the model learns to identify latent relationships between entities. The solution is built using **PyTorch Geometric** and evaluated on a synthetic scale-free network generated via the Barabasi-Albert model.

---

## 🚀 Key Features
- **Synthetic Data Generation:** Simulates realistic "small-world" networks using the Barabasi-Albert algorithm.
- **Deep Learning Model:** A 2-layer GCN encoder with a dot-product decoder.
- **Negative Sampling:** Implements robust training by sampling non-existent edges to prevent overfitting.
- **Visualization:** Interactive plotting of true vs. predicted links using NetworkX.

---

## 🛠️ Installation & Setup

1. **Clone the repository**
git clone 
   cd GCN-Link-Prediction

2.Install Dependencies
    pip install -r requirements.txt

3. Run the Model
    python train.py
