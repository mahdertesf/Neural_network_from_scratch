# Deep Neural Network for Cat vs. Non-Cat Classification 🐱📷

This repository contains my implementation of the final programming assignment from **Course 1: Neural Networks and Deep Learning** of the **DeepLearning.AI Deep Learning Specialization**.

The project focuses on building a deep neural network from scratch (without using high-level deep learning frameworks) to classify images as "cat" or "non-cat."

## 📘 Project Overview

The goal is to implement, train, and evaluate two neural network models:

1. A **2-Layer Neural Network**  
2. An **L-Layer Deep Neural Network**

Both models are constructed using helper functions for parameter initialization, forward propagation, backward propagation, and gradient descent — reinforcing foundational concepts of deep learning.

## 🧠 Key Concepts Covered

- **Network Architecture:**  
  `[LINEAR → RELU] × (L−1) → LINEAR → SIGMOID`

- **Forward & Backward Propagation:**  
  Manual implementation of activations and gradients across all layers.

- **Gradient Descent:**  
  Training the network by minimizing the binary cross-entropy loss.

- **Parameter Initialization & Updates:**  
  Understanding how proper initialization impacts convergence.

- **Data Preprocessing:**  
  Includes reshaping, normalization, and vectorization of image data.

## 📊 Model Performance

| Model                     | Test Accuracy |
|--------------------------|---------------|
| Logistic Regression      | 70%           |
| 2-Layer Neural Network   | 72%           |
| 4-Layer Deep Neural Network | **80%**     |

The deep network demonstrates clear performance gains over simpler models, validating the importance of network depth for image classification tasks.

## 🎓 Source & Acknowledgements

This project is adapted from the **"Deep Neural Network for Image Classification: Application"** assignment from the  
[DeepLearning.AI Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning) on Coursera.

All credit for the original problem, dataset, and instructional materials belongs to DeepLearning.AI and the course instructors:  
**Andrew Ng**, **Kian Katanforoosh**, and **Younes Bensouda Mourri**.

---

> ✨ This project provides hands-on experience with building deep learning models from scratch — an essential step in becoming a proficient AI practitioner.
