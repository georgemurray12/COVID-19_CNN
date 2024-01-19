COVID-19 Diagnosis Using Transfer Learning and CT Images

Introduction

This project focuses on leveraging the power of Convolutional Neural Networks (CNNs) and transfer learning to diagnose COVID-19 using CT images. The goal is to develop a robust machine learning model capable of binary classification to detect the presence of COVID-19.

Project Overview

The task involved constructing and training a 2D CNN model, modifying existing architectures like Resnet-18 or Resnet-50. The project was structured into several key phases:

CNN Construction: Modified Resnet-18 or Resnet-50 for binary classification.
Training from Scratch: The CNN was trained from scratch to understand its baseline performance.
Training with Transfer Learning: Employed transfer learning to enhance the model's performance and compared it with the model trained from scratch.
Model Visualization: Utilized techniques like GradCAM and EigenCAM to visualize and interpret the models.
Throughout the project, three datasets were used: training, validation, and test sets. The success criteria were set such that the test accuracy of both the scratch-trained and transfer learning models needed to exceed 90%.

Technical Summary

Deep Learning Framework: Implemented using PyTorch.
Model Architecture: Adaptation of Resnet-18 or Resnet-50 for binary classification.
Training Approach: Both from scratch and using transfer learning.
Evaluation Metrics: Focus on achieving over 90% accuracy on the test set.
Visualization Techniques: GradCAM and EigenCAM for model interpretation.
Conclusion

This project highlights the effectiveness of transfer learning in enhancing the performance of deep learning models, particularly in medical image analysis for COVID-19 diagnosis. The comparative analysis between the models trained from scratch and with transfer learning provides valuable insights into the benefits of transfer learning in real-world applications.

Please feel free to modify or add any additional details specific to your implementation or results that you observed during the project. ​
