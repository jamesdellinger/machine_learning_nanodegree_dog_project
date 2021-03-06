# Project: Convolutional Neural Network Classifier for dog breeds
*Guess a dog's breed based on an image.*

<img src="https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/mlndlogo.png" height="140">     <img src="https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/dlndlogo.png" height="140">

For Udacity's [Machine Learning Engineer](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009t) and [Deep Learning](https://www.udacity.com/course/deep-learning-nanodegree--nd101) Nanodegrees.

Topic: Deep Learning / Convolutional Networks.

## Overview
* I built a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.
* I first architected my own convolutional neural network from scratch:

    <img src="https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/images/my_cnn.png" height="170">     <img src="https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/images/cnn_graphic.png" height="170">
* I then explored several state-of-the-art CNN models designed for image classification, ultimately using transfer learning to build my own classifier for dog images on top of a pre-trained [Inception v3](https://arxiv.org/abs/1512.00567) bottleneck.
* Given an image of a dog, my algorithm identifies an estimate of its breed:

    <img src="https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/images/sample_dog_output.png" height="170">
* If supplied an image of a human, my code infers the most nearly resembling dog breed:

    <img src="https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/images/sample_human_output.png" height="170">

## Concepts
* Using OpenCV's implementation of [Haar feature-based cascade classifiers](http://docs.opencv.org/trunk/d7/d8b/tutorial_py_face_detection.html) to detect human faces in images.
* Convolutional Neural Network architectures (choosing number of filters, kernel size, stride, and padding).
* Activation functions like relu and softmax.
* Including maxpool layers to decrease dimensionality as network depth increases, and adding dropout layers, to minimize overfitting.
* Flattening the network prior to including fully-connected layers.
* Categorical crossentropy loss function.
* Transfer learning.
* Freezing the bottleneck features of a pre-trained InceptionV3 model to serve as an input layer of my final CNN's fully connected layer:

    <img src="https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/images/my_final_cnn.png" height="170">
* Keras
* TensorFlow

## My Completed Project
* [ipython notebook](https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/dog_app.ipynb) / [html version](http://htmlpreview.github.com/?https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/report.html) / [pdf version](https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/dog_app.pdf)

## Project Grading and Evaluation
* [Project Review](https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/dog_project_review.pdf)

* [Project Grading Rubric](https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/dog_project_grading_rubric.pdf)

## Dependencies
* [requirements-gpu.txt](https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/requirements/requirements-gpu.txt)

* [Anaconda .yml file](https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/requirements/dog-linux-gpu.yml)
