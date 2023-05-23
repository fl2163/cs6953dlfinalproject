# cs6953dlfinalproject

In this project, a generative adversarial network (GAN) de-signed for anime-style photo transformation from the paper AnimeGAN was implemented. The GAN is made of a generator and a discriminator.

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
- Prepare Colab Path for dataset
- Prepare Dataset
- Initialize the Generator and the Discriminator
- Show Summary of the Network Structure
- Main - Training
- References
- Testing
