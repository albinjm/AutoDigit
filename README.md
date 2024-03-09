# Handwritten Digit Recognition with Auto-Encoder Enhanced Neural Networks

![](https://albinjm.github.io/assets/img/AutoDigit.gif)

## Introduction

This project leverages autoencoders, a type of neural network designed for data compression and reconstruction, to denoise images and improve the accuracy of handwritten digit recognition. Utilizing the popular MNIST dataset, which comprises 70,000 labeled images of handwritten digits (0-9), we explore how adding noise to these images and subsequently denoising them with an autoencoder can affect the performance of a digit classifier.

### Project Objective

The primary goal is to demonstrate the effectiveness of autoencoders in image denoising and to evaluate their impact on the performance of classification models. By training an autoencoder with noisy images and using it to denoise test images, we aim to enhance the classifier's ability to recognize digits accurately, providing hands-on experience with key deep learning concepts.

### Dataset

- **MNIST Dataset**: Consists of 70,000 images of handwritten digits, each labeled with the corresponding digit (0-9).

### Methodology

1. **Noise Addition**: Introduce random noise to the MNIST dataset images to simulate real-world imperfections.
2. **Autoencoder Training**: Use the noisy images to train an autoencoder focused on learning efficient data compression and reconstruction.
3. **Image Denoising**: Apply the trained autoencoder to denoise the test images, preparing them for classification.
4. **Digit Classification**: Train a classifier on the denoised images and evaluate its performance compared to its performance on the original noisy images.

### Libraries Used

- **TensorFlow & Keras**: For constructing and training the neural network models, including the autoencoder and the classifier.
- **NumPy**: For handling numerical operations and manipulations within the dataset.
- **Matplotlib**: For visualizing the images, including the original, noisy, and denoised versions, as well as plotting the model's performance metrics.

### Getting Started

To run this project, ensure you have the aforementioned libraries installed in your Python environment. You can install these packages using pip:

```bash
pip install tensorflow numpy matplotlib
