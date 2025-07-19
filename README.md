# 🔢 MNIST Handwritten Digit Classification

A deep learning model that classifies handwritten digits (0–9) using the MNIST dataset. This project showcases fundamental computer vision techniques and neural networks built with PyTorch.

---

## 🎯 Project Overview

This project builds a neural network to classify grayscale images of handwritten digits using the MNIST dataset. It demonstrates a typical image classification pipeline from data loading and preprocessing to training and evaluation.

---

## 🧠 What You’ll Learn

- Image classification fundamentals
- Neural network construction using PyTorch
- Data preprocessing with transforms
- Model training and evaluation
- Accuracy visualization (optional)

---

## 📚 Dataset

- **Source**: [MNIST Database](http://yann.lecun.com/exdb/mnist/)
- **Classes**: 10 (digits from 0 to 9)
- **Images**: 28x28 grayscale (70,000 total: 60k train, 10k test)

No need to manually download — it is loaded automatically using `torchvision.datasets`.

---

## ⚙️ Tech Stack

- **Language**: Python
- **Libraries**: PyTorch, Torchvision, Matplotlib
- **Notebook**: Jupyter Notebook or Google Colab

---

## 📂 Project Structure

```bash
mnist-digit-classification/
├── mnist_digit_classifier.ipynb   # Main notebook
├── README.md                      # Project overview

