**Music Recommendation System**

The goal of this project is to create a Music recommendation system based on unsupervised machine learning recommendation approaches that find and recommend similar music based on the user's preferences

We have explored two types of recommendation systems:
- **Approach 1: Content Based Recommendation System**
In this approach, the attributes of the things a user like is considered as "Content". The system uses the features and likes of the user to provide recommendations to them. In order to determine similarity between the user's past ratings, this method uses cosine similarity
- **Approach 2: Collaborative Filtering Recommendation System**
Here, recommendations are provided to the user based on the previous interactions between the users and the target items. This means, all the past information of the user interaction with the target objects will be sent to the system.

The Content based recommendation is implemented as follows:

    We first created a pipeline which standardizes the data and implements K-Means clustering.
    The clustering was done based on all the numeric features which included audio features. popularity and year.
    We used the elbow method to determine the optimal number of clusters.
    The clusters were visualised with the help of t-sne.
    The recommendation system takes in a dictionary of names of songs and the year it was released in and prints out 10 top recommendations for the user.

The Content based recommendation is implemented as follows:

    We first did exploratory data analysis to understand the data and the users behaviour.
    To solve that issue of memory loss we decided to take the users that have listened to more than 12 songs into account. we generated a user x song matrix.
    KNN was used to calculate the distance between the target song and every other song in our dataset.
    The songs were then sorted according to their distances.
    Tt will then return the top k nearest neighbor songs as song recommendations.

To access the data for content based recommendation system visit the link: https://www.kaggle.com/datasets/vatsalmavani/spotify-dataset
To access the data for collaborative based recommendation system visit the link: http://millionsongdataset.com/
