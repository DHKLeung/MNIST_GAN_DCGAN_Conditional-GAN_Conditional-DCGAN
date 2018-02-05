# MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN

## Generative Adversarial Networks
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/GAN.gif?raw=true)
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/GAN.png?raw=true)

## Conditional Generative Adversarial Networks
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/cGAN.gif?raw=true)
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/cGAN.png?raw=true)

For DCGANs, they are implemented nearly the same as mentioned in the DCGAN paper 
https://arxiv.org/pdf/1511.06434.pdf
According to Ian Goodfellow in NIPS2016, convergence doesn't mean the good generating performance. DCGANs shows it.

## Deep Convolutioinal Generative Adversarial Networks
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/DCGAN.gif?raw=true)
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/DCGAN.png?raw=true)

## Deep Convolutioinal Conditional Generative Adversarial Networks
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/cDCGAN.gif?raw=true)
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/cDCGAN.png?raw=true)

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
* Label Smoothing
