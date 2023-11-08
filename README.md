# Image Generation using GAN

![](generated/generated.gif)

## Generative Adversial Network(GANs)

Generative adversarial networks (GANs) are a class of machine learning algorithms that are used to generate realistic data. GANs consist of two main components: a generator and a discriminator. The generator is responsible for generating data that is similar to the training data, while the discriminator is responsible for distinguishing between real and generated data.

The generator and discriminator are trained in an adversarial manner, which means that they are constantly trying to improve their performance by outsmarting each other. The generator is trying to generate data that is so realistic that the discriminator cannot tell that it is fake, while the discriminator is trying to become so good at distinguishing between real and generated data that it can always tell the difference.

GANs have been used to generate a variety of realistic data, including images, videos, and audio. They have also been used to solve a variety of problems, such as image translation, style transfer, and data augmentation.

A GAN consists of two main components:

1. **Generator:** The generator is responsible for generating data that is similar to the training data. It is typically implemented as a neural network, and it takes a random noise vector as input and outputs a data sample.

2. **Discriminator:** The discriminator is responsible for distinguishing between real and generated data. It is also typically implemented as a neural network, and it takes a data sample as input and outputs a probability that the sample is real.

The generator and discriminator are trained in an adversarial manner. This means that they are trained together, and the goal of each network is to improve its performance by outsmarting the other network. The generator is trying to generate data that is so realistic that the discriminator cannot tell that it is fake, while the discriminator is trying to become so good at distinguishing between real and generated data that it can always tell the difference.

**Training GANs can be challenging. The generator and discriminator can easily get stuck in a Nash equilibrium, where neither network is able to improve its performance any further. There are a number of techniques that can be used to improve the training of GANs, such as spectral normalization, gradient penalty, and batch normalization.**

## About this project

In this repository, I have implemented GANs to generate anime faces.

If you want to explore it yourself, you can simply clone this repo and install the requirements.txt. You can download the dataset from [kaggle](https://www.kaggle.com/datasets/splcher/animefacedataset) or you can create your own API token in kaggle and simply run the cells. It will ask for username and token, enter them and you are all set.