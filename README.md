# Cats vs Dogs Classification using CNN

## Overview
This project implements a Convolutional Neural Network (CNN) from scratch using PyTorch to classify images of cats and dogs. The model was designed to learn hierarchical image features and improve generalization using regularization techniques.

## Approach
- Built a custom CNN architecture with convolutional and fully connected layers
- Applied Batch Normalization after convolutional layers to stabilize training
- Used Dropout in fully connected layers to reduce overfitting
- Applied data augmentation (flips, rotations, normalization) to improve robustness

## Dataset
Cats vs Dogs image dataset (binary classification)

## Insights
- Initial model showed overfitting (higher training accuracy)
- Introducing BatchNorm and Dropout reduced overfitting and improved test accuracy

## Results
- Training Accuracy: 91.91%
- Test Accuracy: 89.80%

## Key Learnings
- Applying Batch Normalization improved training stability and convergence
- Dropout reduced overfitting and improved generalization
- Reducing the gap between training and test accuracy led to a more reliable model

## Tech Stack
- Python
- PyTorch
- NumPy
- Matplotlib

## Future Improvements
- Hyperparameter tuning (learning rate, batch size)
- Experimenting with deeper architectures
- Using transfer learning for improved performance
