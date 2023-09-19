# NATURAL_LANGUAGE_PROCESS_PROJECT
# Amazon Fine Foods Review Analysis

## Project Description
This project aims to analyze and predict product review scores based on fine foods reviews from Amazon. The dataset comprises over 500,000 reviews spanning more than a decade. The project involves data engineering to transform raw text files into a structured CSV format, followed by data preprocessing and machine learning to build predictive models for review scores.

## Data
- **Source**: Amazon product reviews from Oct 1999 - Oct 2012
- **Size**: 568,454 reviews, 256,059 users, and 74,258 products
- **Columns**:
  - Id: Unique row number
  - ProductId: Unique product identifier
  - UserId: Unique user identifier
  - ProfileName: User's profile name
  - HelpfulnessNumerator: Number of users who found the review helpful
  - HelpfulnessDenominator: Number of users who indicated helpfulness
  - Score: Rating between 1 and 5
  - Time: Timestamp for the review
  - ReviewSummary: Brief review summary
  - ReviewText: Text of the review

## Data Transformation (Sprint 1)
We converted the raw text files into a structured CSV format using Python, pandas, and regex. The resulting CSV contains all relevant columns from the raw data.

## Data Preprocessing (Sprint 2 - Task A)
- Tokenization: We tokenized the review text.
- Stopword Removal: Common stopwords were removed.
- Lemmatization: Words were lemmatized for text normalization.

## Building Models (Sprint 2 - Task B)
We trained and evaluated machine learning models to predict review scores, including:
- Logistic Regression
- Decision Tree
- KNN 

We used metrics such as accuracy, precision, recall, and F1-score to assess model performance.

## Results and Discussion
Our best-performing model achieved an accuracy of 85% in predicting review scores. The logistic regression model outperformed other models in terms of interpretability.

## Future Work
- Explore deep learning techniques for text classification.
- Conduct sentiment analysis to gain more insights.
- Deploy the model as a web service for real-time predictions.





