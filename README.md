# KMNIST-GAN
Generation of ancient Japanese Kuzushiji Script using an Adversial Autoencoder GAN


<p align="center">
  <img src="https://github.com/EXJUSTICE/KMNIST-GAN/blob/master/kmnist_examples.png" >
</p>

Kuzushiji-MNIST dataset is a replacement for the MNIST dataset (28x28 grayscale, 70,000 images), provided in the original MNIST format as well as a NumPy format. As MNIST is restricted to 10 classes, one character was chosen to represent each of the 10 rows of ancient Hiragana.
The objective of this tutorial is to demonstrate the capabilities of GAN’s in creating representations that cannot be differentiated from true originals. In a sense,  bringing the extinct Kuzushiji script back to life, by learning from the work of thousands of poets and writers.

Based on the implementation by Erik Lindnoren & Vincent Kao

To run this notebook, a local copy of the Kuzushiji MNIST is required.

Example output:

<p align="center">
  <img src="https://github.com/EXJUSTICE/KMNIST-GAN/blob/master/mnist_88000.png" >
</p>
