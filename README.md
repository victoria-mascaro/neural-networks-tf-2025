# Conv-Autoencoder-FashionMNIST

This project implements a convolutional autoencoder and transfer learning for image classification on the Fashion-MNIST dataset using PyTorch.

## Overview

- Train a deep convolutional autoencoder to learn compressed latent representations of Fashion-MNIST images.
- Reuse the encoder as a feature extractor for a supervised classification task.
- Compare different training schemes:
  1. Training from scratch
  2. Fine-tuning a pre-trained encoder
  3. Frozen random encoder
  4. Frozen pre-trained encoder

## Features

- PyTorch implementation of both autoencoder and classifier
- Training and validation loss and accuracy tracking
- Confusion matrix visualization for performance analysis
- Early stopping and overfitting monitoring

