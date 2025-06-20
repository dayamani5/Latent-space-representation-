# Latent Space Representation for Autoencoders and Variational Autoencoders

This project explores **latent space representations** in Autoencoders (AE) and Variational Autoencoders (VAE), developed as part of the GenAI Internship at Next Hub Technologies.

## Overview

The notebook demonstrates how autoencoders learn to compress and reconstruct data through a latent space — a compact and abstract representation of input data. It also compares regular autoencoders with VAEs, highlighting the probabilistic nature of VAEs and their advantage in generating smooth and meaningful latent spaces.

## Key Components

- **Data Preprocessing:** Using the MNIST dataset for training and testing.
- **Autoencoder Implementation:** A basic encoder-decoder architecture to reduce dimensionality and reconstruct input.
- **VAE Implementation:** Adds a probabilistic twist to autoencoders with a custom loss combining reconstruction and KL divergence.
- **Visualization:** Latent space plots and image reconstructions show how well the models capture data distribution.

## Tools & Libraries

- Python
- PyTorch
- Matplotlib
- NumPy

## Outcomes

The results clearly illustrate the effectiveness of VAEs in generating structured latent spaces compared to traditional AEs. This module offers a strong foundation for understanding generative models.

## Author

Daya Mani – GenAI Intern, Next Hub Technologies
