# Dimensionality-Reduction-and-Image-Reconstruction

Autoencoders for Dimensionality Reduction and Image Reconstruction

This project demonstrates the implementation of Autoencoders, a type of unsupervised neural network architecture used to learn compressed representations of input data. The experiments are conducted using the MNIST handwritten digit dataset.

 Project Overview

An Autoencoder consists of two main components:

	•	Encoder: Compresses the input into a smaller latent space representation.
 
	•	Decoder: Reconstructs the input from the latent representation.

The goal is to minimize the difference between the original and the reconstructed data, enabling applications such as compression, denoising, and feature learning.

 Key Features
	•	Implementation of both shallow and deep autoencoders.
 
	•	Visualization of 2D latent space to interpret digit embeddings.
 
	•	Reconstruction of images from compressed representations.
 
	•	Use of PyTorch for model training and evaluation.

 Technologies Used
	•	Python
 
	•	PyTorch
 
	•	Matplotlib
 
	•	MNIST Dataset (via torchvision.datasets)

  Results
  
	•	Simple autoencoder successfully clusters digits in a 2D latent space.
 
 <img width="380" alt="image" src="https://github.com/user-attachments/assets/5845b422-1606-45a6-afc3-29c09a340e97" />

	•	Full autoencoder achieves effective image reconstructions with minimal loss.
 
	•	Visualization shows how dimensionality reduction can retain essential digit characteristics.
 
 <img width="380" alt="image" src="https://github.com/user-attachments/assets/106483bf-d537-4fb7-8603-ec95f28f13b7" />

