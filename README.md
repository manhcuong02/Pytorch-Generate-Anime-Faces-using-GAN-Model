# Pytorch-Generative-Adversarial-Network

- GAN (Generative Adversarial Network) is a deep learning framework consisting of two neural networks: the generator and the discriminator. The goal of GAN is to generate new data that resembles a given training dataset. The generator learns to create synthetic data samples, such as images or text, while the discriminator learns to distinguish between the real and generated data.

# Deep Convolutional GAN
- DC GAN flowchart (The image is used from Medium: GAN — A comprehensive review into the gangsters of GANs):
  
![](images/dc_gan.jpg)

- Sample: https://www.kaggle.com/datasets/soumikrakshit/anime-faces

![](images/anime_faces_sample.jpg)
- 100 epochs:

![](gifs/dc_gan_anime_faces.gif)

# Wasserstein GAN With Gradient Penalty
- W-gan-gp flowchart(The image is used from Medium: GAN — Wasserstein GAN & WGAN-GP):

![](images/wgan.jpg)

- Sample: https://www.kaggle.com/datasets/soumikrakshit/anime-faces

![](images/anime_faces_sample.jpg)

- 100 epochs:

![](gifs/w_gan_100_epochs.gif)

- 200 epochs:

![](gifs/w_gan_200_epochs.gif)

# Conditional GAN
- C-GAN flowchart (The image is used from Towards data science - cGAN: Conditional Generative Adversarial Network)

![](images/c_gan_model.png)

- Sample: Fashion MNIST

![](images/fashion_mnist_sample.jpg)

- 100 epochs:

![](gifs/fashion_c_gan.gif)

# Pix2Pix: Image-to-image translation with a conditional GAN
- pix2pix GAN flowchart (The image is used from Neurohive: Image-to-Image Translation Neural Network): 

![](images/pix2pix.jpg)

- pix2pix GAN architecture (The image is used from ResearchGate: Exploring sequence transformation in magnetic resonance imaging via deep learning using data from a single asymptomatic patient):

![](images/pix2pix_network_architecture.jpg)

- Sample: https://www.kaggle.com/datasets/splcher/animefacedataset

![](images/gray_sample.jpg)
![](images/rgb_sample.jpg)

- 80 epochs:

![](images/generate_color.jpg)
