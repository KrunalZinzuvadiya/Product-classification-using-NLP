# Product Classification using NLP

## Overview
This project applies **Natural Language Processing (NLP)** and **Machine Learning** to classify product descriptions into predefined categories. The model is trained to automatically categorize products based on their textual descriptions.

## Features
- **Data Preprocessing:**  
  - Cleaning text (removing punctuation, stop words, and special characters).  
  - Tokenization and lemmatization for text normalization.  
  - Feature extraction using **TF-IDF** or **Word2Vec** embeddings.  

- **Machine Learning Models Used:**  
  - Logistic Regression  
  - Naïve Bayes (MultinomialNB)  
  - Support Vector Machine (SVM)  
  - Random Forest Classifier  

- **Performance Evaluation:**  
  - Accuracy, Precision, Recall, and F1-score metrics to assess classification performance.  
  - Model comparison to identify the best-performing classifier.  

## Dataset
The dataset consists of product descriptions labeled into categories such as:
- **Electronics**  
- **Clothing**  
- **Home & Kitchen**  
- **Books**  
- **Beauty & Personal Care**  

## Dependencies
Install the required Python libraries using:

```bash
pip install numpy pandas matplotlib seaborn nltk scikit-learn
