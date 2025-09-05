# U-Net Image Segmentation

## Overview
This project implements the **U-Net architecture** for image segmentation tasks. The notebook demonstrates:
- Data preprocessing and augmentation  
- Building the U-Net model from scratch using deep learning  
- Training the model with annotated datasets  
- Evaluating segmentation performance using metrics  
- Visualizing input images, ground truth masks, and predicted outputs  

This project is particularly useful for applications such as **medical image analysis**, **object detection**, and **scene segmentation**.

## Features
- Clean preprocessing pipeline for segmentation datasets  
- Flexible U-Net model implementation with encoder–decoder architecture  
- Training loop with loss tracking and visualization  
- Performance evaluation (accuracy, IoU, Dice score, etc.)  
- Segmentation results visualization for comparison  

## Files
- **U_Net.ipynb** → Main notebook containing preprocessing, model, training, and evaluation steps  

## Requirements
Install the required Python libraries before running the notebook:
```bash
pip install tensorflow keras numpy pandas matplotlib opencv-python

Usage

Clone the repository:

git clone https://github.com/chabdullah7/U_Net_Image_Segmentation.git
cd U_Net_Image_Segmentation


Open the Jupyter notebook:

jupyter notebook U_Net.ipynb


Run all cells to:

Preprocess dataset

Train the U-Net model

Evaluate and visualize segmentation results

Results

The model outputs segmented masks highlighting regions of interest. Visualizations compare:

Original input image

Ground truth mask

Predicted mask

This helps in assessing model performance visually and quantitatively.

## Author
Abdullah
- GitHub: github.com/chabdullah7
- LinkedIn: linkedin.com/in/ch-abdullah-b537951a
