# CT-Kidney Classification Project

## Overview
The CT-Kidney Classification project focuses on classifying kidney images into four categories: Normal, Cyst, Tumor, and Stone. The project employs deep learning techniques, specifically the ResNet-101 architecture, to achieve accurate classification. This project is developed using Google Colab notebooks.

## Project Structure
The project structure is organized as follows:

CT-Kidney_Classification.ipynb: Google Colab notebook containing the project's code, documentation, and execution environment.
data/
train/: Directory containing training images.
valid/: Directory containing validation images.
test/: Directory containing test images.
models/
resnet101_model.h5: Trained ResNet-101 model saved in Hierarchical Data Format (HDF5).

## Model Training
The CT-Kidney_Classification.ipynb notebook contains the code for data preprocessing, model training, and evaluation. The ResNet-101 architecture is used for image classification, and the model is trained using the provided dataset split into training, validation, and test sets.

## Evaluation
The trained model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score. Additionally, confusion matrices and classification reports are generated to analyze the model's performance on the test dataset.

## Future Improvements
Experiment with different deep learning architectures to improve classification accuracy.
Explore data augmentation techniques to increase the diversity of the training dataset.
Fine-tune hyperparameters such as learning rate, batch size, and optimizer settings for optimal performance.
Conduct further analysis of misclassified instances to identify areas for improvement.

## Contributors
Gokul J
