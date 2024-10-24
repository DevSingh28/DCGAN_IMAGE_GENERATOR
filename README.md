# DCGAN for Anime Face Generation

This project implements a **Deep Convolutional Generative Adversarial Network (DCGAN)** for generating anime face images from random noise. The DCGAN architecture is a class of GANs specifically designed to use convolutional layers, which makes them especially effective for image generation tasks. The primary goal of this project is to train a model capable of generating visually appealing and realistic anime faces.

Generative Adversarial Networks (GANs) consist of two neural networks that compete against each other: the **generator** and the **discriminator**. The **generator** creates fake images that resemble real anime faces, while the **discriminator** attempts to distinguish between real images (from a dataset) and fake images (from the generator). Over time, the generator learns to create increasingly realistic images that can fool the discriminator.

## Dataset

The dataset used for this project is the [Anime Image Dataset](https://www.kaggle.com/datasets/geetmukherjee/anime-image-dataset-deep-learning) from Kaggle, which contains more than 63,000 images of anime faces. The dataset includes high-resolution images that allow the generator to learn and create detailed and diverse anime faces.

### Download and Unzip Dataset

To download the dataset from Kaggle, use the following commands:

```bash
!kaggle datasets download -d geetmukherjee/anime-image-dataset-deep-learning
!unzip anime-image-dataset-deep-learning -d image_data
