Facial Expression Recognition
This project performs facial expression recognition using deep learning on two datasets:

Expression in the Wild (ExpW) Dataset
FER2013 Dataset
I have used transfer learning with MobileNetV2 to classify images into seven emotion categories: angry, disgust, fear, happy, sad, surprise, and neutral. The workflow is identical for both datasets, with only the results (accuracy, confusion matrix, and predicted labels) differing between them.

Datasets
ExpW Dataset: RGB images of faces from diverse environments and conditions.
FER2013 Dataset: Originally grayscale, resized and converted to RGB to work with MobileNetV2.
Project Structure
This repository contains:

expw.ipynb: Code for training and evaluating the model on the ExpW dataset.
fer2013.ipynb: Code for training and evaluating the model on the FER2013 dataset.
Both files will output:

Accuracy: Overall accuracy of the model.
Confusion Matrix: Breakdown of predictions for each emotion category.
Sample Predictions: Examples of predicted labels for a subset of test images.
Results Summary
Dataset	Validation Accuracy	Test Accuracy
ExpW	~57%	60%-
FER2013	~60%	61%-
