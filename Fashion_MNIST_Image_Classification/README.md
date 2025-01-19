# Artificial Neural Networks - Fashion MNIST Image Classification

Dataset Link : https://drive.google.com/drive/folders/1HqL0kdOzzn-AzDYQwxxzkUV5TRHMGyR0?usp=share_link

## Overview
This project involves building and training an Artificial Neural Network (ANN) to classify images from the Fashion MNIST dataset. The dataset contains grayscale images of clothing items, categorized into 10 classes. Using TensorFlow and Keras, this project demonstrates the process of dataset exploration, preprocessing, model building, training, evaluation, and making predictions.

---

## Key Features
- **Dataset Exploration**: Loaded and analyzed the Fashion MNIST dataset using pandas, numpy, and matplotlib.
- **Data Preprocessing**: Normalized pixel values to improve model performance.
- **Model Architecture**: Constructed a simple ANN with Dense and BatchNormalization layers.
  - Learning rate decay mechanism.
  - Regularization techniques to avoid overfitting.
- **Training**: Achieved a validation accuracy of **88%** over 30 epochs using a basic ANN structure.
- **Evaluation**: Measured model performance on a test dataset and visualized predictions with confidence levels.
- **Future Improvements**: Potential enhancements with convolutional and pooling layers for better accuracy and efficiency.

---

## Requirements
Install the following Python libraries before running the project:
- `tensorflow`
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

You can install them with:
```bash
pip install tensorflow numpy pandas matplotlib seaborn

