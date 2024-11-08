## Facial Expression Classification using Deep Learning
### Overview
This project leverages deep learning techniques to classify facial expressions into three categories using a Convolutional Neural Network (CNN) built with PyTorch. The model achieves over 95% accuracy on a challenging dataset, showcasing robust performance on facial expression recognition tasks.

### Features
High Accuracy: Achieved over 95% accuracy on test set.
Custom Loss Function: Utilized a weighted cross-entropy loss to handle class imbalance.
Adaptive Learning Rate: Integrated a ReduceLROnPlateau scheduler for dynamic learning rate adjustment.
Early Stopping & Checkpointing: Implemented techniques to save the best model and prevent overfitting.
Robust Training Pipeline: Includes batch normalization, dropout layers, and progress tracking with tqdm.

### Dataset
The model was trained on a Kaggle facial expression dataset, which contains labeled images for different facial expressions.
Data pre-processing and feature extraction were performed using Pandas and NumPy.

### Model Architecture
Convolutional Layers: Extracted spatial features from facial images.
Batch Normalization & Dropout: Enhanced model generalization and reduced overfitting.
Loss Function: Custom weighted cross-entropy loss to address class imbalance.
Optimization: Used Adam optimizer with learning rate scheduling.
