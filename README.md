# Cat vs Dog Image Classification using HOG Features and SVM

## Overview

This project implements a machine learning pipeline for classifying cat and dog images using Histogram of Oriented Gradients (HOG) feature extraction and a Support Vector Machine (SVM) classifier.

The workflow includes data preprocessing, feature extraction, model training, and performance evaluation on a balanced image dataset.

## Features

* Data quality checking and cleaning
* Image preprocessing and resizing
* HOG feature extraction
* Feature scaling using StandardScaler
* SVM-based classification
* Performance evaluation using Accuracy, Classification Report, and Confusion Matrix
* Data visualization and exploratory analysis

## Dataset

* Microsoft Cats and Dogs Dataset
* Classes: Cat, Dog
* Images Used: 4,000 (2,000 per class)

## Technologies Used

* Python
* OpenCV
* NumPy
* Matplotlib
* Seaborn
* Scikit-Image
* Scikit-Learn

## Model Configuration

* Feature Extraction: HOG
* Classifier: Support Vector Machine (RBF Kernel)
* Training/Test Split: 80/20

## Results

| Metric    | Value  |
| --------- | ------ |
| Accuracy  | 74.75% |
| Precision | 75%    |
| Recall    | 75%    |
| F1-Score  | 75%    |

## Project Structure

```text
cat-vs-dog-classification-svm/
│
├── Cat_vs_Dog_Classification_Using_HOG_and_SVM.ipynb
├── requirements.txt
└── README.md
```

## Installation

```bash
git clone https://github.com/your-username/cat-vs-dog-classification-svm.git
cd cat-vs-dog-classification-svm
pip install -r requirements.txt
```

## Future Improvements

* Hyperparameter tuning with GridSearchCV
* Comparison with other machine learning models
* Deep learning-based image classification
* Streamlit deployment

## Author

Khushi Parekh
