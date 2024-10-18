# Parkinson's Disease Predictor

## Overview

The **Parkinson's Disease Predictor** is a machine learning model that uses the **Support Vector Machine (SVM)** algorithm to predict whether a person has Parkinson's disease based on various voice measurement features. The model has been tested and achieves an accuracy of **87%**, offering a promising tool for early detection of Parkinson's disease.

This project utilizes voice features like MDVP: Fo(Hz), MDVP: Fhi(Hz), MDVP: Flo(Hz), etc., to classify the likelihood of Parkinson's disease.

## Colab Link

You can access the full code implementation on **Google Colab** using this link: [Parkinson's Disease Predictor on Colab](https://colab.research.google.com/drive/1hdWo5J9LAybPKgUg-b0tuIMz03LYUGdS?usp=sharing).


## Features

- **Support Vector Machine (SVM) Algorithm**: Uses SVM for binary classification to predict Parkinson's disease.
- **High Accuracy**: Achieves an accuracy of **87%** on the test dataset.
- **Easy to Use**: User-friendly prediction based on voice measurements.
- **Scalable**: Can be expanded and improved with more data and features.

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Google Colab (for cloud-based computation)

## Dataset

The model is trained on the [Parkinson's Disease dataset](https://archive.ics.uci.edu/ml/datasets/Parkinsons) from the UCI Machine Learning Repository. This dataset contains voice recordings with multiple features that are useful for diagnosing Parkinson's disease.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/parkinsons-disease-predictor.git
   cd parkinsons-disease-predictor
