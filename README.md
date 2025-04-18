**Sentiment analysis**
This notebook trains a sentiment analysis model to classify reviews as positive or negative, based on the text of the review. This is an example of binary—or two-class—classification, an important and widely applicable kind of machine learning problem.

A Large Movie Review Dataset that contains the text of 50,000 movie reviews from the Internet Movie Database is used in notebook to train the model. These are split into 25,000 reviews for training and 25,000 reviews for testing. The training and testing sets are balanced, meaning they contain an equal number of positive and negative reviews.This notebook trains a sentiment analysis model to classify movie reviews as positive or negative, based on the text of the review. Addtionally , MLFLOW has been implemented in the notebook for model experimentation.


**Usecase:**
Anyone who is looking to train a model for binary( or two-class—classification(positive or negative) )  can use this notebook to train the model and perform the model experimentation with MLFLOW which is integrated into this notebook.

**Some real world Usecases which you can use your trained model for**

1.  **Product Reviews (Beyond Movies):**
    * **Application:** Identifying whether customer reviews for products (electronics, books, appliances, etc.) are positive or negative.
    * **Use Case:** Companies use this to understand customer sentiment, identify product issues, and improve customer satisfaction.

2.  **Social Media Monitoring (Brand Sentiment):**
    * **Application:** Analyzing social media posts (tweets, Facebook comments, etc.) to gauge public sentiment towards a brand, product, or event.
    * **Use Case:** Marketing teams track brand perception, identify potential PR crises, and understand customer reactions to campaigns.

3.  **Customer Feedback Analysis (Surveys, Support Tickets):**
    * **Application:** Classifying customer feedback from surveys, support tickets, or chat logs as positive or negative.
    * **Use Case:** Customer support teams prioritize urgent issues, identify areas for improvement, and track customer satisfaction trends.

4.  **Political Sentiment Analysis (Election Monitoring):**
    * **Application:** Analyzing social media posts, news articles, and political commentary to understand public sentiment towards political candidates or policies.
    * **Use Case:** Political campaigns track public opinion, identify key issues, and adjust their messaging.
  
**NOTE**
1)Before you execute the tracking url in notebook make sure to start the MLFLOW UI from command lime using the command below
-> mlflow.set_tracking_uri("http://127.0.0.1:5000")

![image](https://github.com/user-attachments/assets/23ec696c-1836-4e14-addd-ca777103f8d8)

2).See MLFLOW UI.docx for MLFLOW Expermentation screnshots





