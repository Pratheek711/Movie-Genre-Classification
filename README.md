# Movie-Genre-Classification

# Project Overview

This project aims to classify movies into genres based on their plot descriptions using machine learning techniques. The dataset used for this task is the IMDb Genre Classification dataset.

# Dataset Details
  
  Dataset Source: Kaggle - IMDb Genre Classification
  File Format: The dataset is stored in text files with the following format:
  Train Data: ID ::: TITLE ::: GENRE ::: DESCRIPTION
  Test Data: ID ::: TITLE ::: DESCRIPTION
  The dataset contains movie titles, descriptions, and their associated genres.

# Project Workflow

 # Data Loading:
  Read and parse text files into structured format.

 # Text Preprocessing:
  
    Convert text to lowercase
    Remove punctuation and special characters
    Remove stopwords

  # Feature Engineering: 
  Convert text data into numerical representations using TF-IDF.

  # Model Training:
  
  Multi-label classification using Logistic Regression with OneVsRest strategy.
  Evaluated using accuracy score and classification report.
  
  # Prediction & Evaluation: Test model performance on the test dataset.

# Installation & Requirements

To run this project, install the following dependencies:
pip install numpy pandas scikit-learn nltk

# Running the Project

  # Clone this repository:
  git clone <repository-url>
  cd <repository-folder>

  # Run the Python script:
  python movie_genre_classification.py

# Model Performance

The model is evaluated using:
Accuracy Score
Classification Report (Precision, Recall, F1-Score)

# Future Enhancements

Experiment with deep learning models (LSTM, BERT, etc.).
Improve genre classification by handling multiple labels more effectively.
Expand dataset for better generalization.

Author
Pratheek Shetty V

