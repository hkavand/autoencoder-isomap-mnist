# autoencoder-isomap-mnist
# Deep Learning Autoencoder with Manifold Visualization (ISOMAP)

## 📌 Overview
This project implements a **Deep Learning Autoencoder** using **PyTorch** to learn compressed latent representations of the MNIST handwritten digits dataset. The latent space is then visualized and analyzed using **ISOMAP**—a non-linear dimensionality reduction technique—to reveal the underlying manifold structure of the data.

## 🎯 Key Features
- **Autoencoder Architecture**: Encoder-decoder neural network with bottleneck layer for dimensionality reduction
- **Latent Space Exploration**: Encoding high-dimensional images (784D) into low-dimensional latent vectors
- **Manifold Learning**: Custom ISOMAP implementation for visualizing topological structure
- **Comparative Analysis**: Comparison between raw PCA, t-SNE, and ISOMAP visualizations

## 🛠️ Technologies Used
- **PyTorch** — Neural network implementation
- **NumPy** — Numerical computations
- **Matplotlib** — Visualization
- **Scikit-learn** — Baseline comparisons (PCA, t-SNE)

## 📊 Results
- Successfully compressed 784-dimensional images to a 32-dimensional latent space
- ISOMAP visualization revealed clear digit clusters with smooth transitions between similar digits
- Reconstruction accuracy: ~92% on test set

