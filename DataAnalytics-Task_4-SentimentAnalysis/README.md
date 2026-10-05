# Sentiment Analysis Using Machine Learning

## Oasis Infobyte Internship

### Name
Abenet Asnake Tesfaye

### Domain
Data Analytics

### Level
Level 1 - Task 4

## Project Overview

This project focuses on Sentiment Analysis using Natural Language Processing (NLP) and Machine Learning techniques. The goal is to classify tweets as Positive or Negative based on their textual content.

The Sentiment140 dataset containing 1.6 million tweets was used for this analysis. The project includes data preprocessing, text cleaning, feature extraction using TF-IDF, model training, evaluation, and visualization.

---

## Objective

The objective of this project is to:

- Analyze textual data from social media.
- Perform sentiment classification.
- Build machine learning models for predicting sentiments.
- Compare model performance.
- Generate business insights from sentiment analysis.

---

## Dataset

**Dataset Name:** Sentiment140 Dataset

**Dataset Size:** 1.6 Million Tweets

### Features

- target (Sentiment)
- id
- date
- flag
- user
- text

### Sentiment Labels

- 0 = Negative
- 4 = Positive

---

## Tools and Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- TF-IDF Vectorizer
- Scikit-Learn
- WordCloud

---

## Project Workflow

### 1. Data Loading

- Imported Sentiment140 dataset.
- Assigned appropriate column names.

### 2. Data Cleaning

- Removed unnecessary columns.
- Checked missing values.
- Checked duplicate records.

### 3. Text Preprocessing

- Converted text to lowercase.
- Removed special characters.
- Removed stopwords.
- Applied stemming.

### 4. Feature Extraction

- Used TF-IDF Vectorization.
- Converted text data into numerical features.

### 5. Model Building

Two machine learning algorithms were used:

#### Naive Bayes
- Trained on TF-IDF features.
- Evaluated using classification metrics.

#### Logistic Regression
- Trained on TF-IDF features.
- Compared against Naive Bayes.

### 6. Model Evaluation

Performance was evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 7. Visualization

- Sentiment Distribution
- Confusion Matrices
- Positive Word Cloud
- Negative Word Cloud

---

## Key Findings

- Sentiment analysis successfully classified tweets into positive and negative categories.
- The dataset contained a balanced distribution of sentiments.
- TF-IDF effectively transformed textual data into machine learning features.
- Logistic Regression achieved better classification performance.
- Social media data provides valuable customer sentiment insights.

---

## Business Recommendations

1. Monitor customer sentiment regularly.
2. Analyze negative feedback to identify service issues.
3. Improve customer experience based on sentiment trends.
4. Use sentiment insights for marketing campaigns.
5. Integrate sentiment analysis into customer support systems.


## Results

The machine learning models successfully predicted tweet sentiments and demonstrated the effectiveness of Natural Language Processing for sentiment classification.

The project highlights how businesses can leverage customer opinions expressed on social media to improve decision-making and customer satisfaction.

---

## Future Improvements

- Use Deep Learning models such as LSTM.
- Implement BERT-based sentiment analysis.
- Perform multi-class sentiment classification.
- Analyze real-time social media streams.

---

## Author

### Abenet Asnake Tesfaye

Data Analytics Intern

Oasis Infobyte Internship Program

---

