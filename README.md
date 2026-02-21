Book Recommendation System : This project is a web-based Book Recommendation System that suggests books based on user interests and reading patterns. The system recommends books either by overall popularity or by identifying users with similar preferences and suggesting books they enjoyed. The goal of this project was to explore recommendation algorithms, clustering techniques and deploying a machine learning model into a simple web application.

Project Overview : There are thousands of books with high ratings and reviews but readers usually focus on books aligned with their personal taste. This recommender system is built on that idea suggesting books similar to what users already like or what similar readers prefer.

The system uses three datasets:
1. Books dataset – Book information and metadata  
2. Users dataset – User demographic or ID data  
3. Ratings dataset– User ratings for books  

Technical Architecture
1. Data Processing Layer: Data cleaning and preprocessing; Handling missing values ; Merging Books, Users, and Ratings datasets ; Feature engineering for recommendation analysis
2. Recommendation Engine
Popularity-Based Recommendation
- Recommends books with the highest ratings and engagement  
- Useful for general suggestions or new users  

Collaborative Filtering Recommendation
- Groups similar users based on preferences  
- Suggests books liked by users with similar reading habits  

Techniques used:
1. K-Means Clustering - User grouping based on preferences  
2. Truncated SVD (Feature Scaling/Dimensionality Reduction) - Improves performance and reduces complexity  
3. Machine Learning Model
Model trained using processed rating data
Clustering applied to identify similar users  
Recommendations generated dynamically  
4. Web Application Layer
The trained recommendation model is deployed on a web interface:
Flask – Backend framework  
HTML – Page structure  
CSS – Styling and layout  

Users can interact with the interface to receive book recommendations.

Key Features
1. Book recommendations based on popularity
2. Personalized recommendations using collaborative filtering
3. Machine learning clustering model
4. Web interface for easy interaction
5. Dataset-driven recommendation logic  

Learning Outcome : Through this project I learned
1. Recommendation system fundamentals
2. Clustering algorithms (K-Means)
3. Dimensionality reduction with Truncated SVD
4. Data preprocessing techniques
5. Deploying ML models using Flask
6. Integrating ML with front-end web technologies  

Project Vision: This project demonstrates how machine learning can personalize user experiences by analyzing behavior and preferences.  
It highlights the practical use of data science in building intelligent recommendation platforms.

Here are some snapshots,
![Picture1](https://github.com/poonam3030/Book-Recommendation-System/assets/76766910/1b50456e-db88-44e5-9d34-a0a1189ac041)
![Uploading Picture2.png…]()
![Uploading Picture3.png…]()
![Uploading Picture4.png…]()
![Uploading Picture5.png…]()

