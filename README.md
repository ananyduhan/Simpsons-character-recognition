# Simpsons-character-recognition
training a deep learning model to differentiate between simpsons characters 
the inspiration for this project is taken from a video by freeCodeCamp on youtube
here is the link https://youtu.be/oXlwWbU8l2o?si=i33Ldo5fgJvBTZEa

libraries,modulse you need

-os
Imports Python's built-in operating system module. You'll use this to navigate your file system — things like listing folders, building file paths, and checking if files exist. For your project, this is how you'd point to your dataset folder.

-caer
Imports Caer, a computer vision library built on top of OpenCV. It simplifies a lot of the repetitive work in ML pipelines — like loading images from folders, resizing them, and converting them to arrays — all in just a few lines.

-canaro
a companion library to Caer made specifically for building and training neural networks. It works alongside Caer to handle model architecture and training steps without needing to write everything from scratch in TensorFlow/Keras.

-open cv

-numpy
the foundation of almost all ML work in Python. Images are stored and processed as arrays of numbers (pixel values), and NumPy is what lets you manipulate those arrays efficiently.

-gc
Python's built-in garbage collector. Training models can eat up a lot of RAM, especially when loading hundreds of images. You'd call gc.collect() manually at certain points to force Python to free up memory that's no longer being used, keeping things from slowing down or crashing.



what are the steps in training making a deep learning model 
## the data
data is very important in any machine learning or deep learning model this is what defines how the model is gonna be. So, you need to have a good dataset 
and for a deep learning model the more the data better the results but at the same time more computation is required to train the model So, you need to find a balance between them in such a way that it just works 
and at the same time preparing the data is the biggest p[art of making a deep learning model 

### importing the data
the dataset that i have used in this "alexattia/the-simpsons-characters-dataset" from kaggle 
### cleaning the data
the datasets have 20 folders for 20 different characters but the problem is that the some of them have few images as compared so to reduce this imbalance i have taken only the top 10 characters
### resizing the data

### encoding the data
one hot encoder is the best tool for doing such thing 
### splliting training and testing samples 

## the actual model prepration
## training the model
## testing the model




