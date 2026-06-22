# BloodMNIST CNN Image Classification

In this project, Convolutional Neural Network to classify blood cell images from the BloodMNIST dataset.

## Project Overview

The aim of this project is to build and evaluate a deep learning image classification model. The model is trained using BloodMNIST, which contains blood cell images from different classes.

The project includes:

* Loading and preparing the BloodMNIST dataset
* Normalising image data
* Building a CNN model using TensorFlow and Keras
* Training the model
* Evaluating model performance
* Using a confusion matrix to analyse predictions
* Comparing correct and incorrect classifications

## Tools and Libraries Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Scikit-learn
* MedMNIST

## Model Used

A Convolutional Neural Network was used because CNNs are suitable for image classification tasks. The model learns visual patterns from the blood cell images, such as shape, texture, and cell structure.

## Results

The model achieved approximately **91.64% test accuracy**.

The evaluation also includes a confusion matrix to show which classes were predicted correctly and which classes were confused with each other.

## What I Learned

Through this project, I learned how to:

* Prepare image data for deep learning
* Build a CNN model for classification
* Train and evaluate a neural network
* Interpret model accuracy and confusion matrix results
* Understand why some image classes are harder to classify than others

## How to Run

1. Open the notebook file:

   `bloodmnist_cnn_classification.ipynb`

2. Run the notebook in Google Colab or Jupyter Notebook.

3. Install the required libraries if needed:

   ```python
   pip install medmnist
   ```

4. Run the cells from top to bottom.

## Project File

* `bloodmnist_cnn_classification.ipynb`: Main notebook containing the full code, training, evaluation, and visualisations.
