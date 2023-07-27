## Generative Adversarial Networks (GAN)
For this project, I will be designing and training a GAN for image generation.

Training a GAN for image generation can be computationally demanding. Luckily, MNIST dataset provides 28x28 images of handwritten digits, allowing a GAN to be trained more quickly.

### What is a GAN?

A GAN is a deep-learning-based generative model to create synthetic images, videos, music, and text with a real dataset. A GAN operates in the following steps in case of generating images:
1. The generator takes in random numbers and returns an image.
2. This generated image is fed into the discriminator with images taken from the ground-truth dataset.
3. The discriminator takes in both real and fake images and returns probabilities.
4. In a train process, the generator tries to generate synthetic images to deceive the discriminator while the discriminator tries to predict whether the image is real or fake.
