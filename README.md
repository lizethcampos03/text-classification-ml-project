# Text Classification ML Project

## Overview

This project applies supervised machine learning techniques to classify text data across two datasets:

* SMS Spam Detection
* IMDB Sentiment Analysis

The objective is to compare multiple models and evaluate their performance using standard classification metrics.

---

## Datasets

1. SMS Spam Dataset (5,572 messages)
2. IMDB Movie Reviews Dataset (50,000 reviews)

Datasets sourced from Kaggle:

* SMS Spam: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset
* IMDB: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

---

## Methodology

* Text preprocessing using TF-IDF vectorization
* Train/test split (80/20)
* Models implemented:

  * Logistic Regression
  * Naive Bayes
  * Decision Tree
* Hyperparameter tuning using GridSearchCV

---

## Results

* Logistic Regression consistently performed best across both datasets
* Spam dataset achieved ~98% accuracy
* IMDB dataset achieved ~89% accuracy
* Naive Bayes performed well but had lower recall in some cases
* Decision Trees underperformed due to high-dimensional feature space

---

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Project Structure

* `data/` → datasets
* `notebook/` → Jupyter notebook
* `report/` → final PDF report
* `presentation/` → slides

---

## Conclusion

This project demonstrates that classical machine learning models, particularly Logistic Regression, can effectively handle text classification tasks when combined with TF-IDF feature extraction.

---

## Author

Lizeth Campos
