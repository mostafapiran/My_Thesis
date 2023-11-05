# My_Thesis
 My research on the diagnosis of epilepsy is based on brain signals as a master's thesis.
 
 **Thesis Topic:** Design of epileptic activity detection system using deep learning methods from electrocorticographic signals in rats


## Abstract:
According to the World Health Organization, epilepsy is the most common brain disorder
that affects approximately fifty million people worldwide. Epilepsy diagnosis relies on
manual EEG inspection, which is error-prone and time-consuming. Automatic diagnosis
of epileptic seizure from EEG or ECoG signal can reduce diagnosis time and facilitate
treatment targeting for patients. Current detection approaches mainly rely on features that
are manually designed by domain experts. The features are inflexible for recognizing a
variety of complex patterns in large volumes of EEG data. In addition, EEG and ECoG
signals are non-constant, and seizure patterns vary across patients and recording sessions.
EEG and ECoG data always contain many types of noise, which negatively affect the
accuracy of epileptic seizure diagnosis. To address these challenges, deep learning
approaches are reviewed in this paper. The data used in this research were collected from
animal samples (gerbils) and seizures were caused abnormally by drugs. Earth series data
are applied to deep learning networks without any special filter. The only filter used is the
50 Hz notch filter of the utility power. After studying and comparing, convolutional
networks were selected and used to classify the data of this research. The best result was
obtained with 95.22% accuracy and 17.98% error. The designed network produced
promising results for the construction of personalized seizure detectors. Not enough data
was available to increase accuracy and reduce error.

<p align="center">
 <img src="./Doc/3.3.1.jpg">
 <img src="./Doc/3.3.2.jpg">
 <img src="./Doc/3.7.png">
 <img src="./Doc/3.9.png">
 <img src="./Doc/3.10.png">
 <img src="./Doc/4.1.png">
</p>

---

# Convolutional Neural Network (CNN) for Classification using TensorFlow and Keras

## Introduction

This repository contains a Python script that demonstrates the implementation of a Convolutional Neural Network (CNN) for classification using TensorFlow and Keras. CNNs are widely used in deep learning for image classification tasks, and this script serves as an example for building and training a CNN model.

## Code Overview

The Python script provided in this repository performs the following tasks:

1. **Data Loading:** The script loads a dataset from a specified file, in this case, a MATLAB file containing data for a classification task.

2. **Data Preprocessing:** The input data is preprocessed, including resizing images, reshaping, and converting to appropriate data types.

3. **Model Building:** A CNN model is defined using Keras. The model consists of convolutional layers, max-pooling layers, batch normalization, dropout, and fully connected layers.

4. **Model Training:** The model is compiled and trained on the preprocessed data. Training parameters such as batch size and the number of epochs are specified.

5. **Model Evaluation:** The script evaluates the trained model's performance using metrics such as accuracy, precision, sensitivity, specificity, and F1-score.

6. **Confusion Matrix Visualization:** The confusion matrix is displayed to visualize the model's performance in classifying data.

7. **Model Saving:** The trained model and its weights are saved for future use.

## Usage

To use this code for building and training a CNN model:

1. Ensure you have TensorFlow, Keras, NumPy, and OpenCV installed in your Python environment.

2. Replace the dataset path with your dataset file in the line: `dataset = io.loadmat('/content/drive/MyDrive/uni project/2_Class/2sec(1sec_overlap)/D_2c_shuffle_normal_2s(1sec overlap).mat')`

3. Modify the CNN model architecture, training parameters, and evaluation metrics based on your specific task.

4. Run the script to load, preprocess, train, and evaluate the CNN model.

## Contribution and Modification

You are welcome to use, modify, and contribute to this code for your classification tasks. If you find it valuable, consider giving this repository a star.

Feel free to explore the code, experiment with different datasets, and adapt it to your specific use cases. We hope this implementation helps you better understand and apply CNNs in your deep learning projects.

## Acknowledgment

We acknowledge the open-source community and the contributions of TensorFlow, Keras, and other libraries that make it possible to share and collaborate on code like this.

---
