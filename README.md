Potato Leaf Classification with CNN and VGG16
Overview
This repository contains code for a convolutional neural network (CNN) and a VGG16 model trained on the PlanVillage dataset for classifying images of potato leaves into three categories:

Healthy potato leaves
Potato leaves infected with a specific disease
Potato leaves affected by a different disease
The trained models are intended to assist in the automated classification of potato leaf images, which can be helpful for agricultural monitoring and disease detection.

Dataset
The PlanVillage dataset used for training and evaluation consists of labeled images of potato leaves. The dataset is split into training, validation, and test sets, with proper distribution across classes to ensure balanced training.

Models
Two types of models are implemented and evaluated in this repository:

Convolutional Neural Network (CNN): A custom CNN architecture designed for the task of potato leaf classification.
VGG16: A pre-trained VGG16 model fine-tuned on the PlanVillage dataset.

MobileNet- this is a easy to implement and use model which was specially designed for implementing machine learning models on mibles and handy devices which does convolution iun two ways 

Usage
Data Preparation: Ensure that the PlanVillage dataset is properly organized and accessible.
Training: Run the training scripts for the CNN and VGG16 models on the dataset.
Evaluation: Evaluate the trained models on the test set to assess their performance.
Inference: Use the trained models for inference on new potato leaf images for classification.
Requirements
Python 3.x
TensorFlow
NumPy
Matplotlib
Pandas

overall vgg16 gives the highest accuracy

