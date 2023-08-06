# Face_Detection_using_Computer_Vision

## Problem Statement
ABC Ltd wants to explore the implementation of facial recognition technology as a secure and efficient way to grant access to their Board Room. They want a small POC to test the viability of the facial recognition model before considering a full-scale implementation.

## Task
The task is to develop a machine learning model that can recognize and grant access to authorized senior leaders who are allowed to access the Board Room. The model should deny access to any unauthorized individuals. The system should be able to identify and classify users based on facial images.

## Actions Taken
1. Data Collection: Face images of authorized senior leaders were collected. These images were processed and labeled based on the individuals.
2. Data Preprocessing: The collected images were resized to a standard size (32x64 pixels) and transformed into Histogram of Oriented Gradients (HOG) feature descriptors.
3. Model Building: A Support Vector Machine (SVM) classifier was trained using the HOG features to recognize individuals based on their facial images.
4. Model Evaluation: The accuracy of the trained model was evaluated on a test dataset to ensure its performance.

## Model Performance
The developed model achieved an accuracy of 85% on the test dataset, which is considered satisfactory for a POC. The accuracy can be further improved with additional data and fine-tuning.

## Usage
The code files and data in this repository can be used to replicate the POC and adapt it for other use cases or environments.
