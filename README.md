# Imbalanced Email Spam Detection

This repository contains a Jupyter notebook that addresses the challenge of detecting email spam in an imbalanced dataset. The project leverages machine learning techniques to classify emails as either spam or non-spam, taking into account the imbalance in the data distribution.

## Overview

Email spam detection is a common classification task in machine learning. However, due to the significant imbalance between spam and non-spam emails, standard classification techniques often fail to produce good results. This notebook explores different techniques to improve classification performance on an imbalanced dataset.

## Features

- Preprocessing the email dataset to handle imbalance
- Feature extraction and engineering
- Implementation of machine learning models for classification
- Evaluation metrics tailored for imbalanced datasets (precision, recall, F1-score, etc.)

## Dataset

The dataset used in this project contains email samples labeled as **spam** or **non-spam**. Since the dataset is imbalanced, **Class Weightage** technique have been applied to enhance model performance.

You can download the dataset from here: https://www.kaggle.com/datasets/ganiyuolalekan/spam-assassin-email-classification-dataset

## Evaluation

The notebook evaluates model performance using various metrics such as:
- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score

## Models Used
- Logistic Regression 
- Decision Tree 
- Random Forest 


# Results
The results section includes detailed analysis and comparison of different models, highlighting how they perform on the imbalanced email dataset. Special attention is given to recall and F1-score due to the nature of the problem.

Models : F1_score
- Logistic Regression : 0.966
- Decision Tree : 0.964
- Random Forest : 0.967

## Usage

To run the notebook:
1. Clone the repository.

   ```bash
   git clone https://github.com/Vinimesh-Shakya/Imbalanced-Email-Spam-Detection
   ```
2. Install the required dependencies listed in requirements.txt.
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook using Jupyter Notebook or JupyterLab.
   ```bash
   jupyter notebook
   ```

