# 🧠 DeepVision-MNIST: CNN & RNN Architectures in PyTorch

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

## 📌 Executive Summary
This repository contains a complete, end-to-end deep learning pipeline for handwritten digit recognition using the classic MNIST dataset. It demonstrates the implementation, training, and comparative evaluation of two foundational neural network architectures: **Convolutional Neural Networks (CNN)** and **Recurrent Neural Networks (RNN)**. 

Built with PyTorch, this project is designed to showcase clean, modular code, strong understanding of architectural inductive biases, and rigorous model evaluation techniques.

## 🛠️ Technical Stack & Tools
* **Deep Learning Framework:** PyTorch, Torchvision
* **Data Processing:** NumPy
* **Evaluation & Metrics:** Scikit-learn (Confusion Matrix, Classification Reports)
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## 🚀 Key Highlights for Recruiters
* **End-to-End Pipeline:** Handles everything from data ingestion and tensor transformations to training loops and final evaluation.
* **Architectural Diversity:** Implements both spatial (CNN) and sequential (RNN) approaches to image classification, demonstrating versatility in handling different data structures.
* **Rigorous Evaluation:** Goes beyond simple accuracy by utilizing `scikit-learn` for detailed per-class precision, recall, and F1-score analysis, alongside Seaborn-visualized confusion matrices to diagnose misclassifications.
* **High Performance:** Achieves production-tier accuracy on the test set within just 10 epochs of training.

## 📊 Performance Metrics

The models were evaluated on the held-out MNIST test dataset, achieving robust generalization and rapid convergence:

| Metric | Final Value (Epoch 10) |
| :--- | :--- |
| **Training Loss** | `0.0140` |
| **Training Accuracy** | `99.58%` |
| **Test Accuracy** | `99.20%` |

## 💻 Installation & Usage

### 1. Clone the repository
```bash
git clone [https://github.com/your-username/DeepVision-MNIST.git](https://github.com/your-username/DeepVision-MNIST.git)
cd DeepVision-MNIST

```

### 2. Install dependencies

Ensure you have Python 3.x installed, then run:

```bash
pip install torch torchvision matplotlib seaborn scikit-learn numpy

```

### 3. Run the Notebook

Launch Jupyter Notebook to view the code, training loops, and visualizations:

```bash
jupyter notebook MNIST_CNN\&RNN.ipynb

```

## 📁 Repository Structure

* `MNIST_CNN&RNN.ipynb`: The core notebook containing data preprocessing, model classes (CNN & RNN), the training loop, and evaluation visualizations.

---

## 👨‍💻 About the Author

**Nishant Thalwal** *M.Sc. Life Science Informatics*
