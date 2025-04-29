# Sentiment-Analysis-of-Alexa-Product-Reviews
This project applies Natural Language Processing (NLP) and Machine Learning techniques to perform sentiment analysis on Amazon Alexa product reviews. It aims to classify user feedback into positive or negative sentiments, providing insights into customer satisfaction.

## 🧠 Key Features

- **Data Cleaning**: Removed punctuation and stopwords from review text
- **Feature Extraction**: Used `CountVectorizer` for converting text to numeric format
- **Model Training**: Applied `Multinomial Naive Bayes` for classification
- **Performance Metrics**: Evaluated using accuracy, confusion matrix, and classification report
- **Visualization**: WordCloud and bar plots for frequent terms

## 📊 Dataset

- Source: [Amazon Alexa Reviews](https://www.kaggle.com/datasets/sid321axn/amazon-alexa-reviews)
- Fields used: `verified_reviews`, `feedback` (1 = positive, 0 = negative)

## ⚙️ Technologies

- Python
- Pandas, Numpy
- NLTK (Natural Language Toolkit)
- Scikit-learn
- Matplotlib, Seaborn, WordCloud

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/nilsenpai/sentiment-analysis-alexa.git
