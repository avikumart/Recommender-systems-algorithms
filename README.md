# Recommender-systems-algorithms
In this repository, I have shared a notebook containing recommender systems algorithms like apriori, collaborative filtering and SVD using the surprise python library.

## Overview 

Marketing is about connecting the best products or services to the right customers. In today's digital world, personalization is essential for meeting customers' needs more effectively, thereby increasing customer satisfaction and the likelihood of repeat purchases.

Recommender systems are algorithms that recommend the most relevant items to users based on their preferences predicted using the algorithms. it acts on behavioral data, such as customer's previous purchases, ratings, or reviews to predict their likelihood of buying a new product or service.

For example, Amazon's "Customers who bought this item also bought, Netflix Shows and movies you may want to watch" are examples of recommendation systems

## Scope of this repo:

### 1. Association rules mining (Market basket analysis)

- Metrics for association rule mining
 1) Support
 2) Confidence
 3) Lift
 
![image](https://user-images.githubusercontent.com/88608935/193009594-88603bc3-119e-4304-84a3-cf63551371ac.png)

### 2. Collaborative filtering

Collaborative filtering is based on the notion of similarity (or distance). For example, if two users A and B have purchased the same products and have rated them similarly on common rating scale, then A and B can be considered in similar in nature and their buying behaviour. Hence, if A buys a new product and rate high, then that product can be recommended to B and vice-versa.

Collborative filtering comes in two variations:
 1) User-based similarities
 2) Item-based similarities
 

### 3. Using Surprise library (KNNBasic & Matrix factorization)

For real-world implementations, we need a more extensive library which hides all the implamentation details and provides abstract application programming interface(APIs) to build recommender systems. Surprise is a python library for accomplishing this. it provides the following features:

1) Various read-to-use prediction algorithms like neighborhood methods, and matrix factorizaiton-based. it has a built in similarity measures such as cosine, mean square distance(MSD), Pearson correlation coefficient, etc.

2) Tools to evalute, analyze, and compaer the performance of the algorithms. It also provides methods to recommend.
