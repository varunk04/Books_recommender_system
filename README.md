# Books_recommender_system

* Recommendation systems predict the user preferences or ratings that users would give to items. The recommendation system is very highly used in movies, news, advisement, music, etc.

### Types of recommendation systems:

* Usually there are three types of recommendation systems:
1. Popularity based
2. Content Based
3. Collaborative Filtering.

* This project aims to build a Collaborative filtering based recoomendation system.

### Collaborative Filtering:
* user-user collaborative filtering is one kind of recommendation method which looks for similar users based on the items users have already liked or positively interacted with.

![image](https://user-images.githubusercontent.com/100184532/235651085-998b5b3a-1434-4c04-89b6-fe9d0eee1af5.png)

* Each vector in the dataset is represented in a multidimenasional vector space which is used to calculate the similarity score.
* Since the data is represented as a vector, similarity score between each is calculated using the cosine similarity, which is as shown below.

![image](https://user-images.githubusercontent.com/100184532/235652616-4749100f-f570-4c34-b6d2-822123f4180d.png)

This calculated the cosine value is two vecroe and outputs in the range of 0 to 1.
* 0 means two vector are not similiar
* 1 mean vectors are very similar.
