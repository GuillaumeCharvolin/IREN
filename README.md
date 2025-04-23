# Introduction to Neural Networks - Mitochondria Segmentation

This repository contains the report for the project "Introduction to Neural Networks," where I built a pipeline for training a Convolutional Neural Network (CNN) to segment mitochondria. The project utilizes a small U-Net architecture and is part of a pedagogical context.

## Project Overview

The goal of this project was to create and train a CNN model for the segmentation of mitochondria in images. The pipeline includes data preprocessing, model training, and evaluation.

### Key Steps:
1. **Data Preprocessing**: The images are prepared for training by normalizing, augmenting, and splitting the dataset into training and validation sets.
2. **Model Architecture**: A small U-Net architecture was implemented for the segmentation task, which is well-suited for image segmentation problems.
3. **Training and Evaluation**: The model was trained on the dataset and evaluated using common metrics like Intersection over Union (IoU) and Dice coefficient.
4. **Visualization**: Predictions and ground truth masks were visualized for model evaluation.
