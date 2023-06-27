
# Book-Recommendation-SystemThere are numerous items with high ratings and reviews,
but we only pay attention to those that we prefer. The recommender system solely operates on this premise, 
recommending things based on the interests of the consumers. Our goal is to construct a recommender system that proposes
books based on the user's interests, i.e. novels that are similar to books that the user has already liked. 
It can also propose books that comparable people enjoy. Similar users are folks who enjoyed the same books as you.

I used three datasets - Books, Users, and Ratings.

I made two recommendations. One is based on Popularity recommendation, taking books that have higher ratings. 
Second, a Collaborative based recommendation system takes based on users' preferences in the same clusters. 
The model used is K means clustering. 
Feature scaling is Turnacted SVD.

Train the model then presented it on a website by using Flask, HTML, and CSS. 

Here are some snapshots,
![Picture1](https://github.com/poonam3030/Book-Recommendation-System/assets/76766910/1b50456e-db88-44e5-9d34-a0a1189ac041)
![Uploading Picture2.png…]()
![Uploading Picture3.png…]()
![Uploading Picture4.png…]()
![Uploading Picture5.png…]()

