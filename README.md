# Sentiment Analysis on Restaurant Reviews

This GitHub repository demonstrates the creation and training of a Logistic Regression machine learning model for sentiment analysis on restaurant reviews. The model is designed to predict whether a given review is positive or negative based on the text content. The project includes the following key components:

## Overview

1. **Dataset:** The model is trained on a restaurant reviews dataset, which contains customer reviews and a binary indicator of whether they liked the food or not.

2. **Data Preprocessing:** The dataset undergoes preprocessing steps, including text cleaning, stemming, and conversion of textual data to numerical data using TF-IDF vectorization.

3. **Model Training:** A Logistic Regression model is trained on the preprocessed data to predict sentiment based on the reviews.

4. **Model Evaluation:** The accuracy of the model is evaluated on both the training and test datasets.

5. **Model Saving:** The trained model is saved using the `pickle` library for future use.

6. **Integration with GUI Application:** The trained model is integrated into a GUI application. Users can input text, and the application sends it to the model for sentiment analysis, producing a prediction whether the entered text represents a positive or negative review.

## About the Dataset
Dataset link: `https://www.kaggle.com/datasets/d4rklucif3r/restaurant-reviews`
The dataset used for training and testing contains customer reviews and a binary indicator of whether they liked the food or not. This dataset serves as a valuable resource for sentiment analysis and natural language processing tasks.

## Usage

1. **Clone the repository:** `git clone https://github.com/TejusKandipilli/restaurant-reviews-sentiment-analysis.git`
2. **Navigate to the project directory:** `cd restaurant-reviews-sentiment-analysis`
3. **Run the GUI application:** `python app.py`

Feel free to explore the code, dataset, and the trained model. This project serves as an illustrative example of sentiment analysis using natural language processing techniques in a restaurant reviews context.
