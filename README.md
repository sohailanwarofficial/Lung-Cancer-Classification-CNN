# Lung-Cancer-Classification-CNN
Lung Cancer Classification with Convolutional Neural Networks (CNN)

This repository contains code for a Convolutional Neural Network (CNN) model to classify lung cancer cases into three categories: Bengin cases, Malignant cases, and Normal cases.

## Overview

The code in this repository accomplishes the following tasks:

1. Loads and preprocesses a lung cancer image dataset from Google Drive.
2. Divides the dataset into training and testing sets.
3. Defines and trains a CNN model using TensorFlow and Keras.
4. Saves the best model checkpoint based on validation accuracy.
5. Visualizes training and validation accuracy and loss.
6. Computes and displays a confusion matrix and classification report for model evaluation.

## Usage

To use this code, follow these steps:

1. Mount your Google Drive to access the dataset and save the model checkpoint.
2. Set the desired learning rate and other hyperparameters in the code.
3. Run the code to load, preprocess, and train the model.
4. Evaluate the model's performance on the test set.

Make sure to customize the data directory, categories, and other parameters according to your dataset and requirements.

## Dependencies

- Google Colab (for running the code in a Colab environment)
- TensorFlow and Keras (for building and training the CNN)
- scikit-learn (for evaluation metrics)
- NumPy, Matplotlib, and Seaborn (for data manipulation and visualization)

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to modify the code to suit your specific dataset and classification needs.

## Acknowledgments

- Dataset source: [The IQ-OTHNCCD lung cancer dataset] on request
