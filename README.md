# Book-Recommender-system-

![image](https://user-images.githubusercontent.com/70902291/173218363-a35e106e-124a-4f1e-bc1d-9d4206cffc20.png)

A recommendation system is one of the top applications of data science. Every consumer Internet company requires a recommendation system like Netflix, Youtube, a news feed, etc. What you want to show out of a huge range of items is a recommendation system.

# What actually is Recommendation System
A recommendation engine is a class of machine learning which offers relevant suggestions to the customer.  Before the recommendation system, the major tendency to buy was to take a suggestion from friends. But Now Google knows what news you will read, Youtube knows what type of videos you will watch based on your search history, watch history, or purchase history.

A recommendation system helps an organization to create loyal customers and build trust by them desired products and services for which they came on your site. The recommendation system today are so powerful that they can handle the new customer too who has visited the site for the first time. They recommend the products which are currently trending or highly rated and they can also recommend the products which bring maximum profit to the company.

# Types Of Recommendation System
A recommendation system is usually built using 3 techniques which are content-based filtering, collaborative filtering, and a combination of both.

This article was published as a part of the Data Science Blogathon.
source  https://www.analyticsvidhya.com/blog/2021/06/build-book-recommendation-system-unsupervised-learning-project/


A recommendation system is one of the top applications of data science. Every consumer Internet company requires a recommendation system like Netflix, Youtube, a news feed, etc. What you want to show out of a huge range of items is a recommendation system.

Recommendation system image
 


What actually is Recommendation System
A recommendation engine is a class of machine learning which offers relevant suggestions to the customer.  Before the recommendation system, the major tendency to buy was to take a suggestion from friends. But Now Google knows what news you will read, Youtube knows what type of videos you will watch based on your search history, watch history, or purchase history.

A recommendation system helps an organization to create loyal customers and build trust by them desired products and services for which they came on your site. The recommendation system today are so powerful that they can handle the new customer too who has visited the site for the first time. They recommend the products which are currently trending or highly rated and they can also recommend the products which bring maximum profit to the company.

Types Of Recommendation System
A recommendation system is usually built using 3 techniques which are content-based filtering, collaborative filtering, and a combination of both.


# 1) Content-Based Filtering
The algorithm recommends a product that is similar to those which used as watched. In simple words, In this algorithm, we try to find finding item look alike. For example, a person likes to watch Sachin Tendulkar shots, so he may like watching Ricky Ponting shots too because the two videos have similar tags and similar categories.

Only it looks similar between the content and does not focus more on the person who is watching this. Only it recommends the product which has the highest score based on past preferences.

# 2) Collaborative-based Filtering
Collaborative based filtering recommender systems are based on past interactions of users and target items.  In simple words here, we try to search for the look-alike customers and offer products based on what his or her lookalike has chosen. Let us understand with an example. X and Y are two similar users and X user has watched A, B, and C movie. And Y user has watched B, C, and D movie then we will recommend A movie to Y user and D movie to X user.

Youtube has shifted its recommendation system from content-based to Collaborative based filtering technique. If you have experienced sometimes there are also videos which not at all related to your history but then also it recommends it because the other person similar to you has watched it.

# 3) Hybrid Filtering Method
It is basically a combination of both the above methods. It is a too complex model which recommends product based on your history as well based on similar users like you.

There are some organizations that use this method like Facebook which shows news which is important for you and for others also in your network and the same is used by Linkedin too.

![image](https://user-images.githubusercontent.com/70902291/173219201-9ccdf174-9a95-4a7b-a9d0-18f4f1c16007.png)

              Check Out the wondeful article and source
              
              https://towardsdatascience.com/brief-on-recommender-systems-b86a1068a4dd
              
# Dataset- 
## About this Dataset

# Context

During the last few decades, with the rise of Youtube, Amazon, Netflix and many other such web services, recommender systems have taken more and more place in our lives. From e-commerce (suggest to buyers articles that could interest them) to online advertisement (suggest to users the right contents, matching their preferences), recommender systems are today unavoidable in our daily online journeys.
In a very general way, recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy or anything else depending on industries).

Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. As a proof of the importance of recommender systems, we can mention that, a few years ago, Netflix organised a challenges (the “Netflix prize”) where the goal was to produce a recommender system that performs better than its own algorithm with a prize of 1 million dollars to win.

By applying this simple dataset and related tasks and notebooks , we will evolutionary go through different paradigms of recommender algorithms . For each of them, we will present how they work, describe their theoretical basis and discuss their strengths and weaknesses.
              
Link-  https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset


## Application-

## We created application using flask whose front end looks like below-

![image](https://user-images.githubusercontent.com/70902291/173219496-2852c9d8-4548-4cc1-a11c-a69f36fe9bf9.png)

## Recommending Books

![image](https://user-images.githubusercontent.com/70902291/173219529-e64c5528-8b4e-4439-afc3-1568ed9c97bc.png)

## Output of above recommendations 

![image](https://user-images.githubusercontent.com/70902291/173219556-4c1cc25f-a8bf-4112-ae67-37076c22f009.png)


## How to run app ?
```
- Open the project folder in command terminal 
- Type python app.py command 
```


## Source and Links -

- https://youtu.be/1YoD0fg3_EM
- https://towardsdatascience.com/brief-on-recommender-systems-b86a1068a4dd
- https://www.analyticsvidhya.com/blog/2021/06/build-book-recommendation-system-unsupervised-learning-project/

