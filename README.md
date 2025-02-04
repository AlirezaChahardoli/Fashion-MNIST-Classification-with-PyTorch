
## This project features a custom-built Convolutional Neural Network (CNN) for classifying the Fashion MNIST dataset.
# Fashion MNIST Classification with Custom CNN in PyTorch

## 🚀 Project Overview
This project implements a **custom CNN architecture** for classifying the **[Fashion MNIST dataset](https://pytorch.org/vision/0.19/generated/torchvision.datasets.FashionMNIST.html)**, which contains 70,000 grayscale images across 10 clothing categories such as t-shirts, coats, and sneakers.

## 🛠️ Key Features
- **Custom CNN Architecture:** Built from scratch using PyTorch  
- **Skip Connections:** Improve gradient flow and feature extraction  
- **[Learning Rate Scheduling:](https://pytorch.org/docs/stable/generated/torch.optim.lr_scheduler.ReduceLROnPlateau.html)** Optimize training convergence  
- **Comprehensive Model Evaluation: **[Confusion Matrix](https://pytorch.org/ignite/generated/ignite.metrics.confusion_matrix.ConfusionMatrix.html)** (You can use **[Precision](https://pytorch.org/ignite/generated/ignite.metrics.precision.Precision.html) or [Recall](https://pytorch.org/ignite/generated/ignite.metrics.recall.Recall.html)**)  
- **Hyperparameter Tuning:** Achieve optimal training performance  

## 📊 Model Performance
| Metric   | Value |
|----------|-------|
| Training Accuracy | 95%  |
| Test Accuracy      | 93%  |

## 📁 Dataset
The dataset used is **Fashion MNIST**, available directly in **[torchvision.datasets.FashionMNIST](https://pytorch.org/vision/0.19/generated/torchvision.datasets.FashionMNIST.html)**.

## ⚙️ How to Run the Project
1. Clone the repository:
   ```bash
   git clone <https://github.com/AlirezaChahardoli/Fashion-MNIST-Classification-with-PyTorch.git>
   
