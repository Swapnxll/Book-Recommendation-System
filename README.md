# Book Recommendation System
This repository contains a book recommendation system built using Flask and cosine similarity. The system offers two main types of recommendations: a list of top 50 books based on popularity and books similar to user-provided input. It utilizes machine learning techniques to analyze book features and deliver personalized recommendations.

Deployment Link: https://book-recommendation-system-fgf6.onrender.com

This concise description highlights the key features of your project and provides a direct link to the deployed application for further exploration.
#How Euclidean distance is used in the above recommendation system:
Let's consider a simple example where we have three users and their ratings for three movies:
#User	Movie 1	Movie 2	Movie 3
#User A	5	3	2
#User B	4	1	5
#User C	1	4	2

To recommend movies to User A based on the similarity with other users:
Distance between User A and User B:
d(A,B)= 
(5−4) 
2
 +(3−1) 
2
 +(2−5) 
2
 
​
 = 
1+4+9
​
 = 
14
​
 ≈3.74
