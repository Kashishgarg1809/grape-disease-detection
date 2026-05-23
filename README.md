# Deep Learning Based Early Detection of Black Rot in Grape Leaves

A CNN-based image classification model that detects and identifies 
the stage of black rot disease in grape leaves using deep learning.

## Problem Statement
Black rot is a serious fungal disease that damages grape crops 
significantly. Early detection and stage identification through 
image analysis can help farmers take timely action and reduce 
crop loss before it reaches an incurable stage.

## Approach
- Built a Convolutional Neural Network (CNN) using TensorFlow and Keras
- Performed image preprocessing — resizing and normalization
- Dataset sourced from Kaggle and manually organised into 5 
  classes — 4 disease stages and healthy leaves
- Trained the model to classify each leaf image into its 
  respective disease stage
- Evaluated using accuracy and loss curves across training epochs

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## Dataset
Sourced from Kaggle. Images manually organised into 5 classes —
4 stages of black rot infection and healthy grape leaf images.
https://www.kaggle.com/datasets/emmarex/plantdisease/data

## Stages Detected
- Healthy
- Early Infection
- Lesion Expansion
- Advanced Infection
- Terminal (Incurable)

## Results
- Model accuracy: ~88.5%

## How to Run
1. Clone this repository
2. Install dependencies: pip install tensorflow numpy matplotlib
3. Run the script: python your_filename.py
