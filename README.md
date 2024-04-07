# Two Dog Breed Prediction Project

## Overview
This project focuses on the application of deep learning techniques for dog breed classification. Two datasets containing images of dogs belonging to different breeds were analyzed to develop models capable of accurately predicting the breed of a given dog image.

## Dataset
The dataset that is used in this project, each containing images of dogs labeled with their corresponding breeds. The sources of these datasets are as follows:

### File descriptions
train.zip - the training set, you are provided the breed for these dogs
test.zip - the test set, you must predict the probability of each breed for each image
sample_submission.csv - a sample submission file in the correct format
labels.csv - the breeds for the images in the train set

## Methodology
### Data Preprocessing:
The images were preprocessed to standardize dimensions, normalize pixel values, and enhance quality.
Data augmentation techniques such as rotation, flipping, and scaling were applied to increase the diversity of the training dataset.
### Model Architecture:
Convolutional Neural Networks (CNNs) were employed for feature extraction and classification.
Various architectures, including popular ones like VGG, ResNet, and Inception, were experimented with to identify the most effective model.
### Training:
The models were trained on a subset of the dataset and validated on a separate subset to monitor for overfitting.
Transfer learning was utilized by fine-tuning pre-trained models to leverage features learned from large-scale datasets like ImageNet.
## Evaluation:
The performance of the trained models was evaluated using metrics such as accuracy and top-k accuracy.
Confusion matrices and classification reports were generated to assess the model's performance across different dog breeds.
