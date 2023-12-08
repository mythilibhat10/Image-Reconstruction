# Image-Reconstruction
Design Autoencoder for Image Reconstruction

Autoencoders are a neural network that generates an “n-layer” coding of the given input and attempts to reconstruct the input using the code generated. An autoencoder is a regression task that models an identity function. An autoencoder is a neural network that finds the function mapping the features x to itself. 
This objective is known as reconstruction, and an autoencoder accomplishes this through the following process:
  (1) an encoder learns the data representation in lower-dimension space, i.e. extracting the most salient features of the data, and, 
  (2) a decoder learns to reconstruct the original data based on the learned representation by the encoder. 

Application of autoencoder:
  1. Image and Audio Compression: Autoencoders can compress huge images or audio files while
  2. maintaining most of the vital information.
  3. Anomaly Detection: Training the autoencoder on a dataset of normal data and any input that the autoencoder cannot accurately reconstruct is called an anomaly.
  4. Dimensionality Reduction: Autoencoders can lower the dimensionality of high-dimensional datasets. 
  5. Data Generation: Employ autoencoders to generate new data similar to the training data. 
  6. Denoising: One can utilize autoencoders to reduce noise from data. 
  7. Recommender System: Using autoencoders, we can use users’ preferences to generate personalized suggestions.

Image compression:
Image compression involves reducing the pixels, dimensions or color components of images to reduce their file size. This reduces their storage and processing burden (for web performance). Advanced image optimization techniques can identify the more important image components and discard less crucial components. Image compression is a form of data compression, as it reduces the data bits required to encode images but preserves image details.
Image compression can be achieved in deep learning through:
  --> Multi-Layer Perceptrons
  --> Convolutional Neural Networks
  --> Generative Adversarial Networks
