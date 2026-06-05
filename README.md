# Mobile review sentiment analysis

## Overview

This project develops a machine learning system to classify the sentiment of global mobile device reviews into three categories: Positive, Neutral, and Negative. The project follows a complete machine learning workflow, from data preprocessing and feature engineering to model evaluation and optimization.

## Objectives

* Build an end-to-end sentiment classification pipeline.
* Compare the performance of multiple machine learning algorithms.
* Improve model generalization through time-based validation and hyperparameter tuning.
* Identify the most influential features affecting sentiment prediction.

## Dataset

The dataset contains mobile device reviews collected from multiple smartphone brands, including Samsung, Apple, Xiaomi, Motorola, Google, OnePlus, and Realme.

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn

## Methodology

### Data Processing

* Data cleaning and preprocessing
* Feature engineering
* Handling categorical variables
* Time-based feature extraction

### Model Development

Three machine learning algorithms were implemented and evaluated:

* Naive Bayes
* Random Forest
* XGBoost

### Model Optimization

* Time-based Block Cross-Validation
* Hyperparameter tuning
* Early Stopping
* Hold-out evaluation on unseen data

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score

## Results

The comparative analysis showed that XGBoost achieved the best overall performance, outperforming Naive Bayes and Random Forest across all evaluated brands.

Key findings:

* XGBoost achieved F1-scores above 0.92 across all brands.
* Time-based Block Cross-Validation improved the reliability of model evaluation.
* Rating, Reputation Score, and Device Model were identified as the most influential features.

## Repository Structure

```text
metrics/
plots/
predictions/
Mobile Reviews Sentiment.csv
Naive_Bayes.ipynb Random_Forest.ipynb
XGBoost.ipynb
README.md
```

## Future Improvements

* Apply advanced NLP techniques on review text.
* Experiment with transformer-based models such as BERT.
* Deploy the model as a web application.

## Author

Le Nguyen Minh Thu
