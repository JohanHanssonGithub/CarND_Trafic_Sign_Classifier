# CarND_Trafic_Sign_Classifier

## Build a Traffic Sign Recognition Project

The goals / steps of this project are the following:

 * Load the data set (see below for links to the project data set)
 * Explore, summarize and visualize the data set
 * Design, train and test a model architecture
 * Use the model to make predictions on new images
 * Analyze the softmax probabilities of the new images
 * Summarize the results with a written report
 
 

## Rubric Points

## Here I will consider the rubric points individually and describe how I addressed each point in my implementation.


### 1. Provide a Writeup / README that includes all the rubric points and how you addressed each one. You can submit your writeup as markdown or pdf. You can use this template as a guide for writing the report. The submission includes the project code.

You are reading it right know, and here is the link: https://github.com/JohanHanssonGithub/CarND_Trafic_Sign_Classifier/tree/master/CarND-Traffic-Sign-Classifier-Project


## Data Set Summary & Exploration
### 1. Provide a basic summary of the data set. In the code, the analysis should be done using python, numpy and/or pandas methods rather than hardcoding results manually.

* Number of training examples = 34799
* Number of testing examples = 12630
* Image data shape = (34799, 32, 32, 3)
* Number of classes = 43

## Design and Test a Model Architecture

# 1. Describe how you preprocessed the image data. What techniques were chosen and why did you choose these techniques? Consider including images showing the output of each preprocessing technique. Pre-processing refers to techniques such as converting to grayscale, normalization, etc. (OPTIONAL: As described in the "Stand Out Suggestions" part of the rubric, if you generated additional data for training, describe why you decided to generate additional data, how you generated the data, and provide example images of the additional data. Then describe the characteristics of the augmented training set like number of images in the set, number of images for each class, etc.)

I belive that the shape was the most importent factor, and if you would use this in a real care lighting would change and effect colour. So the picture were converted to grayscale. I also normolized the pictures Picture=Picture-128/128, this reduced the size of the images. 
