# 🔢 MNIST Handwritten Digit Classification

A neural network built with TensorFlow/Keras to classify handwritten digits (0–9) using the MNIST dataset. It achieves over 97% accuracy on test data and includes model evaluation and error visualization.

---

## 🎯 Overview

This project demonstrates a full pipeline for classifying grayscale images of handwritten digits using a dense neural network. It covers:

- Data loading and preprocessing
- Model building and training
- Evaluation using confusion matrix and accuracy
- Visualization of predictions and errors
- Saving the trained model

---

## 📚 Dataset

- **Source**: [MNIST Database](http://yann.lecun.com/exdb/mnist/)
- **Images**: 28×28 grayscale
- **Training Set**: 60,000 samples
- **Test Set**: 10,000 samples
- Automatically loaded via `tf.keras.datasets.mnist`

---

## ⚙️ Tech Stack

- **Language**: Python
- **Libraries**: 
  - TensorFlow / Keras
  - NumPy, Pandas
  - Matplotlib, Seaborn
  - scikit-learn (for confusion matrix)

---

## 📂 Project Structure

```bash
mnist-digit-classification/
├── mnist_digit_classifier.ipynb   # Main notebook
├── mnist_simple_model.h5          # Saved trained model
