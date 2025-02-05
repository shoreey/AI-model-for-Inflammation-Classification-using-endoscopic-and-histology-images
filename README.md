Inflammation Classification Using Endoscopic and Histology Images

Project Overview

This project focuses on classifying inflammation in the bowel (rectum and sigmoid) using both endoscopic and histology images. The data pipeline was designed to seamlessly integrate .mat files containing 15 frames of endoscopic images with an Excel sheet containing diagnostic results.

Frameworks Used

TensorFlow

PyTorch

Data Pipeline

Connected .mat files with corresponding diagnostic results from the Excel sheet.

Extracted 15 frames from endoscopic videos.

Applied data augmentation techniques including resizing, cropping, normalization, and converting images to tensors.

Model Training

Three pre-trained models were used to classify inflammation:

EfficientNet

ResNet50

DenseNet

Evaluation Metrics

ROC (AUC)

Classification Report: Precision, F1 Score, Recall, Accuracy

Confusion Matrix: True Negative (TN), True Positive (TP), False Positive (FP), False Negative (FN)

Training and Validation Accuracy & Loss

Model Performance Comparison

The models were compared based on the above evaluation metrics to determine the most effective model for inflammation classification.


Conclusion

This study provides a robust approach to inflammation classification using both endoscopic and histology images, leveraging state-of-the-art deep learning models and comprehensive evaluation metrics.
