# Patient-Condition_Classification
*Patient condition classification*, which predicts the medical issue of a sentence and recommends drugs to prevent or treat that issue, involves the use of natural language processing (NLP) and machine learning techniques to analyze text input and provide relevant medical information. 
![Project Flow Architecture](Project flow.webp)

## Project Overview

This project focuses on classifying the condition of a patient based on their reviews, enabling the recommendation of suitable drugs. The implementation leverages Natural Language Processing (NLP) techniques through a structured pipeline.

## NLP Pipeline Steps

1. **Tokenization:**
   - Break down sentences into individual tokens.

2. **Clean Reviews:**
   - Remove punctuation.
   - Eliminate special characters and numbers.
   - Convert text to lowercase.
   - Perform lemmatization.

3. **Bag of Words Model:**
   - Create a bag of words model to vectorize the preprocessed reviews.

4. **Apply ML Algorithms (Naive Bayes, Passive Aggressive Classifier):**
   - Train and test the model using Naive Bayes and Passive Aggressive Classifier.

5. **TFIDF Model:**
   - Create a TFIDF model to vectorize the preprocessed reviews.

6. **Apply ML Algorithms (Naive Bayes, Passive Aggressive Classifier):**
   - Train and test the model using Naive Bayes and Passive Aggressive Classifier.

7. **Comparison:**
   - Evaluate and compare the performance of both models.

## Project Demo

[![Project Demo](https://example.com/path/to/your/demo.gif)](https://example.com/path/to/your/demo.gif)

## Running the Project

To run the project, execute the following command:

```bash
python app.py
# or
flask run
