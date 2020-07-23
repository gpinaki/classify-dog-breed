## Dog Breed Classifier Project from Udacity

### Project Overview

We've developed an application with following functionalities:
* Get dog image as input - The program detects that this is a dog image and predict the breed
* Get a human image - The program detects that this is a human image and displays a breed that mostly resembles with the face
* Get an image that is neither dog nor human - The program returns a text saying the image is neither dog nor human
* Get an image with both human and dog - The program will detect both. It also predicts the dog breed from the dog image detected.

### Implementation Overview

In this project, we've used a pre-trained model to detect a dog. Then, I have used Keras to build a Convolutional Neural Network (CNN) from scratch. Finally, I've used the Transfer Learning technique to use a pre-trained model in our CNN model. 
Let's break down the work into multiple steps as mentioned below.
Import and load the required dataset
 Write a function  to detect human face from the input image
 Write a function to detect dog from the input image
 Create a CNN from scratch to classify dog breeds 
 Create a CNN using transfer learning to classify dog breed (for better accuracy and performance)
 Write the algorithm as per the project requirement mentioned as above
 Test the algorithm
 
### Import Datasets

Following datasets are supplied by Udacity. Refer the links in the notebook.

* The dog dataset
* The human_dataset

### Acknowldgements
This is a capstone project from Udacity Data Science Nanodegree program. The code structure, templates etc are provided by Udacity. 


My blogpost link related to this project is [this](https://medium.com/@pinaki.guha/dog-breed-classification-project-using-cnn-4daa02bed23).
