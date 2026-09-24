# Fake News Detection

## Overview

A Natural Language Processing project for detecting whether a news article is Fake or Real using Machine Learning.

The project uses text preprocessing, TF-IDF feature extraction, and Logistic Regression for classification.

## Dataset

Fake and Real News Dataset.

The dataset is downloaded using KaggleHub.

The dataset contains two categories:

* Fake News
* Real News

## Technologies

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn
* WordCloud
* TF-IDF
* Logistic Regression

## Data Preparation

The dataset contains separate files for Fake and Real news articles.

The title and article text were combined into a single text field.

Labels were assigned as:

* Fake = 0
* Real = 1

## Text Preprocessing

The text was preprocessed using:

* Lowercasing
* HTML removal
* URL removal
* Removing non-alphabetic characters
* Stopword removal
* Lemmatization

## Feature Extraction

TF-IDF (Term Frequency-Inverse Document Frequency) was used to transform the news articles into numerical feature vectors.

Both unigrams and bigrams were used to capture individual words and short phrases.

## Classification Model

A Logistic Regression classifier was trained to classify news articles into:

* Fake
* Real

## Evaluation

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Classification Report
* Confusion Matrix

The model achieved approximately **99% F1-score** on the test set.

## Visualization

The project includes:

* Confusion Matrix
* Fake News Word Cloud
* Real News Word Cloud
* Most important features for each class

## Prediction

A prediction function was implemented to classify new news text as either:

* Fake
* Real

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Then open:

`Fake_News_Detection.ipynb`

Run the notebook cells sequentially.

The dataset will be downloaded automatically using KaggleHub.

## Project Structure

```text
Fake-News-Detection/
├── Fake_News_Detection.ipynb
├── README.md
└── requirements.txt
```

## Note

The dataset is not included in this repository. It is downloaded automatically through KaggleHub.

The project is intended for educational and research purposes. Test-set performance does not necessarily represent performance on real-world news from unseen sources.
