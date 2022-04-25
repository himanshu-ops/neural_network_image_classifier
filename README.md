## Introduction

The main goal of this tutorial is to create an image classifier from scratch using the Keras package. You will create a binary classifier based on an object type of your choice. The classifier will accept images and then predict whether or not a given image contains that object. For example, if you chose your object to be a cat, then the classifier would accept images and predict 1 if it believes there is a cat in the image or a 0 if not.

1. Preparing the dataset
Step 1: You need to choose an object. The object can be anything but for simplicity I have chosen a basket ball.
Step 2: Create a dataset by taking 80 pictures of you chosen object and 80 pictures of other things that are not your object. From these 160 images you will create a training set (50 object/50 not object), a validation set (15 object/15 not object), and a test set (15 object/15 not object). It’s best if your dataset is diverse, so take pictures of the chosen object with, for example, different lighting, from different angles, different distances from camera, different examples of the same type of object. Similarly for the not object images: try to include a variety of objects in different ways.

## Libraries required:

```os, os.path
numpy
pathlib
matplotlib
tensorflow
keras
IPython.display
```

Read the following blog for a step by step tutorial: https://medium.com/@himancodes/building-an-image-classifier-from-scratch-using-convolutional-neural-networks-c9ebcde3a53e

About me: https://himanshu-ops.github.io/index.html

Kindly reach out to me on this email: hbcan9@gmail.com for any concerns and clarifications.
