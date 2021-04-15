# Convolutional-Neural-Network

# Goal
This exercise is one of my first tries at implementing a convolutional NN. 

My goal is to develop a CNN model to accurately classify new images, using transfer learning.

The dataset contains 6,899 images from 8 distinct classes compiled from various sources.
The classes include airplane, car, cat, dog, flower, fruit, motorbike and person.

The dataset can be downloaded on Kaggle [natural images](https://www.kaggle.com/prasunroy/natural-images).

The exercise is written in R code. 

# Approach
## Part 1: Data Preparation

Downloading and organizing the images into train, validation, and test directories.

## Part 2: Modeling using feature extraction

I'm applying a pre-trained model, using use a feature extraction approach for transfer learning.
I'm using the publicly available VGG16 model (trained on mostly animals and everyday objects) as a convolutional base.
The representations learned by the VGG16 network are used to extract features from the the new dataset. I will then run these newly extracted features through a densely-connected classifier, which is build and trained from scratch.

# Result
I was able to achieve a test accuracy of 99,93%!


*Check out the code in the .rmd or the .html files.*
