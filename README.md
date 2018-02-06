# MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN

For DCGANs, they are implemented nearly the same as mentioned in the DCGAN paper. https://arxiv.org/pdf/1511.06434.pdf

According to Ian Goodfellow in NIPS2016, convergence doesn't mean the good generating performance. DCGANs showed it.

The parameters and model of Conditional-DCGAN were saved in the folder "Trained_Conditional-DCGAN_Generator". They are in parts because of the upload limit in GitHub. However, since the files of model saved can't be split using ```$zip -s``` linux command and I don't know why. So I zip the whole files and use old school command ```split -b 99M``` to do that.

## How to use the trained Conditional-DCGAN Generator
If you are in Linux, use the command ```cat model_parameters_ckpt.zip.part* > model_parameters_ckpt.zip``` to assemble them. If you are in Windows, please use Git Bash and type the same command mentioned. Afterthat, run the the Jupyter Notebook "Trained_Conditioinal-DCGAN_Generator.ipynb" and it will retrieve the parameters. The demo of using the generator is shown in the notebook. Feel free to alter the code and generate what you want.

Trained Conditional-DCGAN output demo:
![](https://raw.githubusercontent.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/master/img_for_readme/trained_generator.jpg)

## Generative Adversarial Networks
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/GAN.gif?raw=true)
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/GAN.png?raw=true)

## Conditional Generative Adversarial Networks
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/cGAN.gif?raw=true)
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/cGAN.png?raw=true)

## Deep Convolutional Generative Adversarial Networks
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/DCGAN.gif?raw=true)
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/DCGAN.png?raw=true)

## Conditional Deep Convolutional Generative Adversarial Networks
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/cDCGAN.gif?raw=true)
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/cDCGAN.png?raw=true)

## Development Environment
* Ubuntu 16.04
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
