# WGANs-with-gradient-penalty

![image](https://github.com/Ruthvik9/WGANs-with-gradient-penalty/assets/74010232/50b98771-e598-46e2-ba05-7f9ca1d44e1a)


![image](https://github.com/Ruthvik9/WGANs-with-gradient-penalty/assets/74010232/aea597eb-0f14-4957-a137-4d173e2f0db4)

This repository contains a detailed implementation of the Wasserstein Generative Adversarial Network with Gradient Penalty (WGAN-GP), based on the paper "Improved Training of Wasserstein GANs" by Gulrajani et al.

## Introduction
Generative Adversarial Networks (GANs) are powerful generative models capable of producing high-quality, realistic images. However, training GANs can be challenging due to issues like mode collapse and unstable training dynamics. The Wasserstein GAN with Gradient Penalty (WGAN-GP) introduces a new objective function and regularization term that helps mitigate these issues and improves the stability of GAN training.

## Project Description
In this project, a WGAN-GP model is implemented and trained on the CelebA dataset, a large-scale face attributes dataset with more than 200,000 celebrity images. The model consists of a generator network that generates new faces and a critic network that aims to distinguish between real and generated faces.

Key Features of this Implementation:

Data Loading and Preprocessing: Implemented a custom data loader for efficiently loading and preprocessing CelebA images, which includes resizing and normalizing the images.
Model Architecture: Built the generator and critic models using convolutional layers in PyTorch, following the architecture guidelines suggested in the original WGAN-GP paper.
Training Procedure: Developed a robust training loop which includes efficient computation of the gradient penalty for stable training, updating the generator and critic models using the Adam optimizer, and tracking the training progress by logging the losses.
Performance Visualization using **weights and biases**: Included functionality for visualizing the generated faces during training, which provides a clear indication of the model's performance and progression.
