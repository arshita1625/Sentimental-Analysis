SENTIMENTAL ANALYSIS

This project involves performing sentiment analysis on Amazon Alexa reviews. The goal is to classify customer reviews based on their sentiment, such as positive, negative, or neutral. The dataset used in this project contains reviews for Amazon Alexa, and the sentiment analysis is performed using natural language processing (NLP) techniques and machine learning algorithms.
The dataset used in this project is from Amazon reviews on the Alexa product. The dataset contains various attributes such as review text, rating, and sentiment. The file used for analysis is:

--File Name: amazon_alexa.tsv
--File Type: Tab-separated values (TSV)
Columns:
-Review: The review text written by the customer.
-Rating: The rating given by the customer (typically between 1 and 5).
-Sentiment: The sentiment label assigned to the review (Positive, Negative, or Neutral).
NOTE: The dataset is located in the Data/ folder.

Libraries:
-pandas: For data manipulation and loading.
-nltk: For text preprocessing and sentiment analysis.
-scikit-learn: For machine learning algorithms and model evaluation.
-matplotlib / seaborn: For data visualization.
-xgboost: For training the machine learning model.

<img width="666" alt="Screenshot 2024-11-11 at 1 53 40 AM" src="https://github.com/user-attachments/assets/4059cf3c-dadd-4955-9656-4a00cc256bf1">

<img width="582" alt="Screenshot 2024-11-11 at 1 54 26 AM" src="https://github.com/user-attachments/assets/94e61560-173e-460d-86a8-38bab0540c8e">

<img width="579" alt="Screenshot 2024-11-11 at 1 54 38 AM" src="https://github.com/user-attachments/assets/535c0bc3-c67f-4f01-8913-260d74d066aa">
<img width="574" alt="Screenshot 2024-11-11 at 1 54 55 AM" src="https://github.com/user-attachments/assets/c40c2fc7-e39d-494f-9c8d-0300f673b339">

<img width="605" alt="Screenshot 2024-11-11 at 1 56 00 AM" src="https://github.com/user-attachments/assets/df0b5490-ad6a-4239-abc4-2820af1e5340">



--The sentiment analysis model will classify reviews into the following categories:

-Positive: Reviews with a high rating (typically 3 or 4 or 5).
-Negative: Reviews with a low rating (typically 1 or 2).

The output includes:

-A classification of each review's sentiment.
-Performance metrics for the model (accuracy, precision, recall, F1-score).
-Visualizations of sentiment distributions.
