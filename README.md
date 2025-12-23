# Plant Disease Classification Project

This project performs **plant disease classification** from leaf images using **Convolutional Neural Networks (CNNs)**. It supports preprocessing, training, validation, and prediction on new images.

---
## Dataset
https://www.kaggle.com/datasets/karagwaanntreasure/plant-disease-detection/data

## Features

1. **Image Classification**
   - Detect multiple plant diseases.
   - Supports multi-class classification.
   - Uses pretrained CNN backbones (ResNet, EfficientNet).

2. **Preprocessing**
   - Resize images to fixed size (e.g., 224x224).
   - Normalize to mean/std.
   - Optional data augmentation: flips, rotations, brightness/contrast changes.

3. **Training & Evaluation**
   - Train/validation split.
   - Metrics: Accuracy, F1-score, Confusion Matrix.
   - GPU support for faster training.

4. **Prediction**
   - Predict disease class on new images.
   - Visualize predicted class and confidence.

---

## Installation

1. Clone the repository:

git clone https://github.com/yourusername/plant-disease-classification.git
cd plant-disease-classification

2. Install dependencies 

pip install -r requirements.txt

## Usage
1. data preprocessing
2. Training
3. Predict on New Images
