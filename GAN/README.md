### Image classification 
The goal of this project was to develop and compare two Generative Adversarial Network (GAN) models for generating realistic images using the CIFAR-10 dataset — a collection of 32×32 color images across 10 object categories (e.g., airplanes, cats, horses, etc.).

Two architectures were implemented:

- Basic GAN: Built with fully connected layers in both the generator and discriminator. Images were generated from a random noise vector by progressively upscaling it to a 32×32×3 image.

- DCGAN (Deep Convolutional GAN): Utilized convolutional layers. The generator used Conv2DTranspose layers to reconstruct images from the latent space, while the discriminator used Conv2D layers with LeakyReLU activation to better capture spatial features.

Both models were trained on the same dataset and evaluated based on the visual quality of the generated images.
