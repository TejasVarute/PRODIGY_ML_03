# Cat vs Dog Classification using Support Vector Machine (SVM)

## Overview

This project implements a **Support Vector Machine (SVM)** to classify images of cats and dogs using the **Kaggle Cats and Dogs Dataset**. SVM is a supervised machine learning algorithm, particularly effective for binary classification tasks. This project preprocesses image data, extracts features, and trains an SVM model to distinguish between cats and dogs.

## Features

- **Image Preprocessing**:
  - Resizes and normalizes images for uniform feature extraction.
- **Feature Extraction**:
  - Uses Histogram of Oriented Gradients (HOG) or pre-trained deep learning models for feature generation.
- **SVM Classification**:
  - Trains an SVM classifier with the extracted features for accurate image categorization.
- **Evaluation Metrics**:
  - Accuracy, precision, recall, and confusion matrix to assess model performance.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - OpenCV: For image processing.
  - scikit-learn: For SVM implementation and evaluation.
  - NumPy: For numerical operations.
  - matplotlib & seaborn: For visualization.
  - PIL (Pillow): For image handling.

## Example Workflow

### Preprocessing
- Resize all images to a uniform size (e.g., 128x128).
- Convert images to grayscale for simplicity.

### Feature Extraction
- Use **HOG** (Histogram of Oriented Gradients) for feature extraction.
- Optionally, use features from a pre-trained model like VGG16 or ResNet.

### SVM Training
- Train the SVM classifier with a radial basis function (RBF) kernel for optimal separation of features.

### Evaluation
- Calculate metrics: accuracy, precision, recall, F1-score.
- Display confusion matrix and a few misclassified examples.

## Future Enhancements

- Add real-time image classification functionality using a webcam or uploaded images.
- Optimize the pipeline for large datasets using distributed computing.
