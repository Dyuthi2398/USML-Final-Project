**Music Recommendation System**

The goal of this project is to create a Music recommendation system based on unsupervised machine learning recommendation approaches that find and recommend similar music based on the user's preferences
-Approach 1: Content Based Recommendation System. In this task, we have used K-Means clustering algorithm to cluster songs based numeric audio features like valence, acousticness, danceability etc to recommend songs based on artist, genre and song names.
-Approach 2: Collaborative Filtering Recommendation System In this task, songs are recommended based on similar user’s preferences with the help of KNN and SVD         algorithm.



We have implemented five variations of the models:

    Baseline XGBoost Ranker using Tfidf vectors
    Cosine Similarity on Fasttext Word embeddings
    Pre-trained DistillBERT model
    Pre-trained Roberta Model
    Pre-trained XLNet Model

Additionally we have implemented three variations of ensemble models:

    Ensemble of equal weightage to DistillBERT, Roberta and XLNet Model
    Ensemble of different weightage to DistillBERT, Roberta(50%) and XLNet Model
    Ensemble of equal weightage to DistillBERT and Roberta Model

We were able to achieve the score of 0.84 using the Ensemble model of DistilBert and Roberta Models.

To access the data visit the link: https://www.kaggle.com/competitions/AI4Code/data
