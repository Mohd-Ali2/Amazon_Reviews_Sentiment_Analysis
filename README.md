# Amazon Reviews Sentiment Analysis

This project performs sentiment analysis on Amazon reviews using TF-IDF and SVM.

## Setup

Install dependencies with:

pip install pandas numpy matplotlib seaborn scikit-learn nltk

## Usage:
Prepare the dataset: Place amazon_reviews.csv in the same directory.
Run the script: It preprocesses the text, trains an SVM model, and makes predictions.

Key Functions:
Preprocessing: Cleans and tokenizes text, removes stopwords and numbers.
Model Training: Uses TF-IDF features and SVM for classification.
Prediction: Classifies new review text.

## Example
To classify a new review:

input = 'It works, but file writes are a bit slower...'
input = preprocess_text(input)
input = tfidf_vectorizer.transform([input])
prediction = model.predict(input)
print(prediction)

License
MIT License
