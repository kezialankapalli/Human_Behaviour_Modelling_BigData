# Human_Behaviour_Modelling_BigData

# Overview
Understanding human behavior through social media data is a challenging yet powerful approach in data science. This project explores how advanced machine learning techniques can be used to extract meaningful insights from large-scale, unstructured data. By applying Naive Bayes, Logistic Regression, Long Short-Term Memory (LSTM), and Random Forest, we aim to predict behavioral patterns with high accuracy. The ability to analyze human interactions on social media can benefit businesses, policymakers, and researchers by providing valuable insights into trends and decision-making processes.

Social media generates vast amounts of data in the form of likes, shares, comments, and views. Effectively processing and analyzing this data requires robust techniques in data preprocessing, feature engineering, and model selection. Our approach incorporates feature encoding methods such as CountVectorizer and TfidfVectorizer to transform textual data into numerical representations, which are then fed into predictive models. With a user-friendly interface built using Streamlit, this project enables interactive visualization of predictions, making human behavior analysis more accessible and interpretable.

# Dataset
The dataset used in this project is sourced from Kaggle and contains 34,972 rows and two columns. It consists of social media text-based interactions, making it well-suited for analyzing behavioral patterns. The dataset underwent preprocessing, including the removal of user handles and stopwords, to enhance the accuracy of predictions.

# Machine Learning Models Used
Logistic Regression: A statistical model effective for binary classification tasks.
Naive Bayes: A probabilistic classifier known for its efficiency in text classification.
Random Forest: An ensemble learning technique that improves model robustness and accuracy.
LSTM (Long Short-Term Memory): A type of recurrent neural network (RNN) designed to capture sequential dependencies in data, making it ideal for time-series behavior analysis.

# Results
After training and evaluating the models, we observed the following accuracy scores:
Logistic Regression: 78%
Naive Bayes: 74%
Random Forest: 82%
LSTM: 88%

The LSTM model achieved the highest accuracy at 88%, making it the most effective approach for analyzing sequential behavioral patterns in social media data. Random Forest followed closely with 82%, demonstrating strong performance in handling structured text features. Logistic Regression and Naive Bayes also provided decent results, with Naive Bayes being particularly useful for text classification tasks.

