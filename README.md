# MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN

**** Cost/Loss over iterations are presented in jupyter notebooks ****

## Generative Adversarial Networks
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/MNIST_GAN_samples/evolution.gif?raw=true)

## Conditional Generative Adversarial Networks
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/MNIST_Conditional-GAN_samples/evolution.gif?raw=true)

## Deep Convolutioinal Generative Adversarial Networks
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/MNIST_DCGAN_samples/evolution.gif?raw=true)

## Deep Convolutioinal Conditional Generative Adversarial Networks
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/MNIST_Conditional-DCGAN_samples/evolution.gif?raw=true)

## Development Environment
* Ubuntu 14
* Jupyter Notebook
* TensorFlow(GPU) 1.4.1
* NumPy 1.14.0
* Pandas 0.21.1
* SciPy 1.0.0
* ImageIO 2.2.0
* Matplotlib 2.1.1

## Tricks
* Adjusting learning rate seperately for Discriminator and Generator
* Accourding to Ian Goodfellow on NIPS 2016, sometimes convergence doesn't mean good generating performance, and this shown in DCGAN
* Label Smoothing
