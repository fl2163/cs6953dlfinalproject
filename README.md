# CS-6953 DL Final Project

In this project, a generative adversarial network (GAN) designed for anime-style photo transformation from the paper AnimeGAN was implemented. The GAN is made of a generator and a discriminator. The goal of the generator is to produce samples that are indistinguishable from real data. The discriminator network on the other hand tries to distinguish between real data samples from the training dataset and the synthetic samples created by the generator, and learns to classify whether a given sample is real or fake. 

Compared to previous style transfer models, the Anime-GAN employees a more lightweight design that reduces the computational complexity and memory requirements. It also improved the anime-styled effect and texture by using special loss functions such as grayscale style loss, grayscale adversarial loss and color reconstruction loss.


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

Note: currently, the default epoch number is set to 100 epoch. However it takes long time to train. For demonstration purpose the 'full' version includes final effect of using pretrained weights. The training step can also be run with less epochs but the result would be less optimal.  

The style of the anime effect, can be set to either 'Hayao' or 'Shinkai' for training using the 'Initialize Overall Network Settings' parameters. Currently the demonstrations are using the 'Hayao' style.
Note: currently, the default epoch number is set to 100 epoch. However it takes long time to train. For demonstration purpose the 'full' version includes final effect of using pretrained weights. The training step can also be run with less epochs but the result would be less optimal.  
