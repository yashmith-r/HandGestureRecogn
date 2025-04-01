# Hand Gesture Recognition Using Sign Language

## Overview
This project uses a **Convolutional Neural Network (CNN)** to recognize hand gestures based on the **Sign Language MNIST** dataset. The dataset contains images representing letters of the American Sign Language (ASL) alphabet. The goal of this project is to classify these images into the corresponding ASL letter.

This code will allow you to:
- **Train** a CNN model on the dataset.
- **Test** the model’s accuracy on a validation/test set.
- **Use a webcam** to recognize hand gestures in real-time using the trained model.

## Dataset
- **Dataset Name:** Sign Language MNIST
- **Source:** [Kaggle - Sign Language MNIST Dataset](https://www.kaggle.com/datasets/datamunge/sign-language-mnist)
- **Description:** The dataset contains **28x28 pixel grayscale images** of hand gestures representing **A-Z letters** in the American Sign Language alphabet. The dataset consists of **27,455 images**.

## Requirements

Before running the project, you need to install the following Python libraries:
- **TensorFlow** (for building and training the neural network)
- **NumPy** (for numerical computations)
- **Matplotlib** (for visualizing training progress)
- **OpenCV** (for webcam integration)
- **Scikit-learn** (for data preprocessing)

Install the dependencies using pip:

```bash
pip install tensorflow numpy matplotlib opencv-python scikit-learn
