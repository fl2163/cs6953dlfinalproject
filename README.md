# cs6953dlfinalproject

In this project, a generative adversarial network (GAN) designed for anime-style photo transformation from the paper AnimeGAN was implemented. The GAN is made of a generator and a discriminator. The goal of the generator is to produce samples that are indistinguishable from real data. The discriminator network on the other hand tries to distinguish between real data samples from the training dataset and the synthetic samples created by the generator, and learns to classify whether a given sample is real or fake.

Python Notebook Outline

- Initialize weights
  - initially set to noise data
- Establish Five Component Blocks of the Generator Network
  - serves as building block for the generator.
- Generator Network
  - define the architecture of the generator.
- Discriminator Network
  - define the architecture of the discriminator.
- Initialize Overall Network Settings
  - set the parameters such as epoch, learning rate, file directories.
- Prepare VGG19
  - vgg19 is used to obtain base value for loss to speed up the training
- Initialize Loss Functions
- Helper Functions
- Prepare Colab Path for dowloading the datasets
- Prepare Dataset
- Initialize the Generator and the Discriminator
- Show Summary of the Network Structure
- Main - Training
- Testing
- References
