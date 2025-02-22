# Waste Classification Using Transfer Learning

# Project Overview
This project aims to automate waste classification using deep learning. By leveraging transfer learning with the VGG16 model, the model can accurately distinguish between recyclable and organic waste based on image data.

# Dataset
The dataset is sourced from Kaggle's Waste Classification Dataset and consists of labeled images of waste materials categorized as organic (0) or recyclable (1).

# Model Development
Use the pre-trained VGG16 model for feature extraction.
Add custom classification layers for waste classification.
Freeze initial layers and train the model.

# Fine-Tuning & Training
Unfreeze some layers to refine the model.
Train the model on the dataset and track performance metrics.

# Evaluation & Visualization
Plot accuracy/loss curves for training and validation sets.
Test the model on unseen images and visualize predictions.

# Results
The trained model successfully classifies waste images with high accuracy, demonstrating the effectiveness of transfer learning in automated waste sorting.
