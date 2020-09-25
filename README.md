# Face_Recognition

# Project Description	
In this hands-on project, the goal is to build a face identification model to recognize faces.


# Dataset: Aligned Face Dataset from Pinterest
This dataset contains 10.770 images for 100 people. All images are taken from 'Pinterest' and aligned using dlib library.


# Overview
In this problem, we use a pre-trained model trained on Face recognition to recognize similar faces.
Here, we are particularly interested in recognizing whether two given faces are of the same person or not. Below are the steps involved in the project.

●	Load the dataset and create the metadata.
●	Check some samples of metadata.
●	Load the pre-trained model and weights.
●	Generate Embedding vectors for each face in the dataset.
●	Build distance metrics for identifying the distance between two given images.
●	Use PCA for dimensionality reduction.
●	Build SVM classifier to map each image to its right person.
●	Predict using the SVM model.

# Instructions for all the above steps are given in the notebook.

# Project Objectives	
The objective of the project is to learn how to do transfer learning and how to use a pre-trained model already trained on the desired task. In this project you are going to use transfer learning to build face detection model and face recognition using pre-trained model The goals of this assignment are as follows:


●	Using a pre-trained model to do Face Recognition.
●	Learn to use Triplet Loss.
●	Learn to use SVM classifier for prediction.
●	Learn to combine both the models to test
