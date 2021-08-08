# Creating-GANs
This is an idependent project that aims to develop and train a Generative Adversarial Network. We are training out network on the [11k Hands Dataset](https://sites.google.com/view/11khands). Our goal is to create a GAN that is able to draw images of right/left dorsal/palm facing hands. 

Running the code requires the user to have a machine that can download and process the 11k Hands Dataset. The code also requires the following modules: numpy, matplotlib, pandas, tensorflow. 

As of July 2021, we have processed and cleaned the 11k Hands Dataset to include black and white images of hands that do not have nail polish, accessories, or abnormalities that are stored as numpy arrays. We have also constructed a neural network that is trained to identify right/left dorsal/palm facing hands from these images. Our next steps in the fall are to improve the accuracy of our network by adding complexity and layers. We also plan to being constructing our GAN. 
