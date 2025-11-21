# Fake News Categorization

## Project Goal
The goal of this project is to classify news articles as either **Fake News** or **Factual News** using Natural Language Processing (NLP) techniques and machine learning models.

## Main Steps
1. **Data Loading & Exploration**: Load the dataset and explore its structure and label distribution.
2. **POS Tagging & Named Entity Recognition (NER)**: Use SpaCy to extract part-of-speech tags and named entities from the text.
3. **Text Preprocessing**: Clean and prepare the text data for analysis.
4. **Sentiment Analysis**: Analyze the sentiment of the articles using VADER.
5. **Feature Engineering**: Convert text into numerical features using techniques like TF-IDF or CountVectorizer.
6. **Model Training & Evaluation**: Train multiple classification models and evaluate their performance.

## Models Used
- Logistic Regression
- Naive Bayes (MultinomialNB)
- Random Forest
- SGD Classifier
- LDA / LSI (for topic modeling)

## Required Packages & Libraries
Run the following command to install all necessary dependencies:

```bash
pip install vaderSentiment gensim spacy pandas matplotlib numpy seaborn nltk scikit-learn
