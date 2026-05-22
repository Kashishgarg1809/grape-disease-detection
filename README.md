# Deep Learning Based Early Detection of Black Rot in Grape Leaves

A CNN-based image classification model that detects and identifies 
the stage of black rot disease in grape leaves using deep learning.

## Problem Statement
Black rot is a serious fungal disease that damages grape crops 
significantly. Early detection and stage identification through 
image analysis can help farmers take timely action and reduce 
crop loss.

## Approach
- Built a Convolutional Neural Network (CNN) using TensorFlow and Keras
- Performed image preprocessing — resizing and normalization
- Dataset manually separated and organised into 4 stages of 
  black rot infection plus healthy leaves
- Trained the model to classify leaves into their respective 
  disease stages
- Evaluated using accuracy/loss curves and confusion matrix

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## Dataset
Sourced from Kaggle. Images manually organised into 4 stages 
of black rot infection along with healthy grape leaf images.
[Add your Kaggle dataset link here]

## Classes / Stages Detected
- Healthy
- Stage 1 — Early infection
- Stage 2 — Moderate infection
- Stage 3 — Severe infection
- Stage 4 — Advanced infection

## Results
[Add your accuracy and loss curve screenshots here]

## How to Run
1. Clone this repository
2. Install dependencies: pip install tensorflow numpy matplotlib
3. Run the script: python your_filename.py
