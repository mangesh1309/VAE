# Variational Autoencoder (VAE) Implementation using TensorFlow

This repository contains an implementation of a Variational Autoencoder (VAE) using TensorFlow. VAEs are a type of generative model that learn to encode and decode high-dimensional data in a continuous latent space, enabling the generation of new data samples.

## Overview

A Variational Autoencoder consists of an encoder network that maps input data to a distribution in the latent space, and a decoder network that reconstructs the input data from samples drawn from this distribution. VAEs are trained using variational inference and optimize a reconstruction loss along with a regularization term that encourages the learned latent space to follow a prior distribution.

## Files

1. `VAE`: Implementation of a Variational Autoencoder using TensorFlow for encoding and decoding high-dimensional data.


## Usage

The `VAE` file contains the implementation of the VAE model. To train the model and reconstruct input data, simply execute the Python script:

