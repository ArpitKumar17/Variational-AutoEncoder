# Variational Autoencoder (VAE) using TensorFlow and Keras

This repository contains an implementation of a **Variational Autoencoder (VAE)** built using TensorFlow and Keras. It supports both the **MNIST** and **Fashion-MNIST** datasets for training and evaluation.

---

## 🧠 Overview

A **Variational Autoencoder (VAE)** is a generative model that learns to encode input data into a latent space and decode it back to the original space. Unlike traditional autoencoders, VAEs learn a probabilistic distribution of the latent space, which enables sampling and generation of new, similar data.

---

## 📦 Features

- Implemented using `TensorFlow`, `Keras`, `NumPy`, and `Matplotlib`
- Works with both `MNIST` and `Fashion-MNIST` datasets
- Modular architecture using classes:
  - `Encoder`
  - `Decoder`
  - `VAE` (combines both and defines training logic)
- Custom loss function combining:
  - Reconstruction loss (Binary Crossentropy)
  - KL Divergence
- Custom `train_step()` and `test_step()` methods
- Visualizes the reconstructed and generated images during training

---

