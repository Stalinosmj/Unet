# Medical Image Segmentation using U-Net

This project implements a U-Net model for medical image segmentation using the Kvasir-SEG dataset. The goal is to accurately segment polyps in colonoscopy images.

## Project Structure

The project is organized as follows:

- **Setup**: Installs necessary libraries.
- **Data Loading and Splitting**: Downloads and unzips the Kvasir-SEG dataset, defines functions to load images and masks, and splits the data into training, validation, and testing sets.
- **Dataset and DataLoader**: Creates a custom PyTorch Dataset and DataLoader for handling the image and mask data.
- **U-Net Architecture**: Defines the U-Net model architecture.
- **Model Summary**: Displays a summary of the U-Net model.
- **Dice Coefficient and Loss Functions**: Implements Dice Coefficient, IoU Score, Binary Cross Entropy, a Shape-Aware Loss, and a combined loss function.
- **Training Loop**: Contains the code for training the U-Net model, including an early stopping mechanism and learning rate scheduler.
- **Model Evaluation on Test Set**: Evaluates the trained model on the test set using various metrics.
- **Visualization of Results**: Visualizes the segmentation results on sample images from the test set.

## Setup

To run this notebook, you need to install the required libraries. This is done in the first code cell using `pip`:
