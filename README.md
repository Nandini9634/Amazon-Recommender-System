# Amazon-Recommender-System

## Abstract 

Online shopping is all over the internet. All our needs are just a click away. The biggest online shopping website is Amazon. Amazon is known not only for its variety of products but also for its strong recommendation system. Recommender systems have become an integral part of e-commerce sites and other businesses like social networking, movie/music rendering sites.

## Dataset

In my project I am taking into consideration the amazon review electronics dataset which has 4 attributes.
1. User ID : Every user identified with a unique id.
2. Product ID : Every product identified with a unique id.
3. Rating : Rating of the corresponding product by the corresponding user .
4. Time Stamp : Time of the rating.: 

## What I have done

I have used the given two models in my project : 

Collaborative filtering (Item-Item recommendation):

Collaborative filtering is commonly used for recommender systems. These techniques aim to fill in the missing entries of a user-item association matrix. CF is based on the idea that the best recommendations come from people who have similar tastes. In other words, it uses historical item ratings of like-minded people to predict how someone would rate an item.Collaborative filtering has two sub-categories that are generally called memory based and model-based approaches.

Model-based collaborative filtering system: 

These methods are based on machine learning and data mining techniques. The goal is to train models to be able to make predictions. For example, we could use existing user-item interactions to train a model to predict the top-5 items that a user might like the most. One advantage of these methods is that they are able to recommend a larger number of items to a larger number of users, compared to other methods like memory based approach. They have large coverage, even when working with large sparse matrices.

And I have used KNNwithmeans model to train the dataset

## Result

It recommends top 25 highly correlated products in sequence.
