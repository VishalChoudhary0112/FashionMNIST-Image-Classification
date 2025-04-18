# FashionMNIST Image Classification with TinyVGG CNN

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)

A PyTorch implementation of TinyVGG CNN for classifying FashionMNIST images, achieving 88.93% test accuracy.

## Table of Contents
- [Project Overview](#-project-overview)
- [Results](#-results)
- [Installation & Usage](#-installation--usage)
- [Project Structure](#-project-structure)
- [Key Features](#key-features)
- [Model Architecture](#-model-architecture)
- [Training](#-training)
- [Performance Insights](#-performance-insights)
- [License](#-license)

## 📌 Project Overview

This project implements a Convolutional Neural Network (CNN) using the TinyVGG architecture to classify images from the FashionMNIST dataset. The model achieves 88.93% testing accuracy with a loss of 0.315, demonstrating strong performance in recognizing fashion items.

**Dataset Details:**
- FashionMNIST (60,000 training + 10,000 test images)
- 10 classes (T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot)
- Grayscale images of 28x28 pixels

## 🚀 Results

| Metric        | Value   |
|--------------|---------|
| Test Accuracy | 88.93%  |
| Test Loss     | 0.315   |

Confusion matrix and sample predictions:

![Sample Predictions](https://via.placeholder.com/600x400?text=Sample+Predictions) *(replace with actual image)*

## 🛠️ Installation & Usage

### Prerequisites
- Python 3.7+
- PyTorch 1.8+
- Jupyter Notebook (optional)

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/fashionmnist-cnn.git
cd fashionmnist-cnn
