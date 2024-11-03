# CNN-Image-Classification
## Description
This is a part of the Neural network course elaboration.\
Make an image classifier using a convolutional neural network.

1. Define Gaussian filter, a Sobel X filter, and a Sobel Y filter:

What do the three filters (Gaussian, SobelX, SobelY) do to the original image?

Gaussian filter is used for denoising, Here we can see that by applying gaissian filter to the image, the image is smoother than the original image.\
Sobel X & sobel Y are an spatial filter used for edge detection in horizontal and vertical directions respectively. Here we can see in second image the edge and features of image in horizontal axis better and in third image the edge and features of image in vertical axis.
 

>>>>>>> f0bbc471422ac4f26905f9e4f0e398ea9cf93946
## Data 
Images used in this code are from CIFAR 10.
CIFAR 10: The CIFAR-10 dataset contains 60,000 32x32 color images in 10 different classes. The classes represent airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. There are 6,000 images in each class. 
CIFAR-10 dataset: https://en.wikipedia.org/wiki/CIFAR-10

## libes
* from scipy import signal, misc 
* import numpy as np
* from keras.datasets import cifar10
* from sklearn.model_selection import train_test_split


## Files

$ jupyter notebook
Recommend install jupyter through anaconda here.

References
