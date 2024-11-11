Sentiment Analysis 
This project involves performing sentiment analysis on Amazon Alexa reviews. The goal is to classify customer reviews based on their sentiment, such as positive, negative, or neutral. The dataset used in this project contains reviews for Amazon Alexa, and the sentiment analysis is performed using natural language processing (NLP) techniques and machine learning algorithms.

The dataset used in this project is from Amazon reviews on the Alexa product. The dataset contains various attributes such as review text, rating, and sentiment. The file used for analysis is:
File Name: amazon_alexa.tsv
File Type: Tab-separated values (TSV)
Columns:
Review: The review text written by the customer.
Rating: The rating given by the customer (typically between 1 and 5).
Sentiment: The sentiment label assigned to the review (Positive, Negative, or Neutral).
The dataset is located in the Data/ folder.
Model XGBOOST is used
<img width="719" alt="Screenshot 2024-11-11 at 1 44 21 AM" src="<img width="572" alt="Screenshot 2024-11-11 at 1 44 39 AM" src="https://github.com/user-attachments/assets/03eef928-6a1d-40ac-92e6-bb204e0b8c2f"><img width="576" alt="Screenshot 2024-11-11 at 1 44 49 AM" src="https://github.com/user-attachments/assets/aceba198-a1b0-4d71-9132-1943e425c0d2">
<img width="564" alt="Screenshot 2024-11-11 at 1 45 06 AM" src="https://github.com/user-attachments/assets/601fe178-eef8-4045-aa73-972962243934">
<img width="354" alt="Screenshot 2024-11-11 at 1 45 16 AM" src="https://github.com/user-attachments/assets/9fc5f08e-bd7e-4410-9406-84d620256a8c">

https://github.com/user-attachments/assets/d9b7be82-b5b5-4f1b-8760-1db4711cf35e">
<img width="1070" alt="Screenshot 2024-11-11 at 1 45 56 AM" src="https://github.com/user-attachments/assets/e87cbfdb-e370-40a3-b3ed-5b284a27232c">

<img width="915" alt="Screenshot 2024-11-11 at 1 45 27 AM" src="https://github.com/user-attachments/assets/d58a47dc-e760-4b9a-9c95-911173eab00f">

The sentiment analysis model will classify reviews into the following categories:

Positive: Reviews with a high rating (typically 4 or 5).
Negative: Reviews with a low rating (typically 1 or 2).
Neutral: Reviews with a rating of 3.
