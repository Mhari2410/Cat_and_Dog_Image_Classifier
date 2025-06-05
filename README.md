

# Dog vs. Cat Classification

## Overview

This project is a machine learning model trained to classify images as either dogs or cats. It utilizes traditional machine learning algorithms — **Support Vector Machine (SVM)** and **Logistic Regression** — to perform image classification based on extracted features.

## Dataset

The model was trained on a dataset consisting of thousands of labeled images of dogs and cats. The dataset was preprocessed and split into training, validation, and test sets to train and evaluate the model's performance.

## Feature Extraction

Since SVM and Logistic Regression require fixed-size feature vectors, raw images were first resized and converted to grayscale. Features were extracted using techniques such as:

* Pixel intensity flattening
* Histogram of Oriented Gradients (HOG)
* Or other relevant feature descriptors

## Model Architecture

Instead of deep learning, this project uses:

* **Support Vector Machine (SVM)** with a suitable kernel for high-dimensional separation.
* **Logistic Regression** for linear classification.

These models were trained on the extracted features to learn the distinction between dog and cat images.

## Performance

Both models achieved reasonable accuracy on the test set. SVM performed slightly better due to its capability in handling complex decision boundaries, while Logistic Regression provided a simpler and faster alternative.

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the provided Jupyter notebook to:

   * Extract features from new images
   * Train the models (optional)
   * Make predictions using trained models

## Future Improvements

Possible future enhancements include:

* Trying advanced feature extraction techniques like SIFT or SURF.
* Adding more preprocessing steps such as normalization and augmentation.
* Comparing performance with deep learning models like CNNs.
* Hyperparameter tuning using grid search or cross-validation.

## Credits

This project was developed by Haripriya R.
If you have any questions or suggestions, feel free to contact me at **[rharipriya234@gmail.com](mailto:rharipriya234@gmail.com)**.


