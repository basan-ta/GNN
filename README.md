@@@ Dynamic Movie Recommendation System using Graph Neural Networks (GNNs)

Welcome to my major year project repository! This project focuses on building a dynamic movie recommendation system using Graph Neural Networks (GNNs). The system is designed to provide personalized movie recommendations by leveraging the power of graphbased machine learning.

@@@ Overview of my project

Traditional recommendation systems often rely on collaborative filtering or matrix factorization techniques, which can struggle to capture complex relationships between users and items. In this project, I use GNNs to model the recommendation problem as a graph, where:
Nodes represent users and movies.
Edges represent interactions (e.g., a user rating a movie) or relationships (e.g., a movie belonging to a specific genre).

By treating the recommendation problem as a graph, the system can capture both direct and indirect relationships, leading to more accurate and personalized recommendations.

@@@ Here are some ley Features:

1. GraphBased Representation:
   Users and movies are represented as nodes in a graph.
   Edges capture interactions (e.g., ratings) and relationships (e.g., genres, actors).

2. Dynamic Recommendations:
   The system adapts to new data in realtime such as user interacation tracking, making it suitable for dynamic environments where users and movies are constantly updated.

3. Personalization:
   The GNN model considers both direct usermovie interactions and indirect relationships (e.g., movies liked by similar users having same interest or age group) to provide highly personalized recommendations.

4. Scalability:
   The system is designed to handle largescale datasets, making it suitable for realworld applications.

@@@ Here it works?

1. Graph Construction:
   The input data (e.g., usermovie ratings, movie metadata) is transformed into a graph structure.
   Nodes represent users and movies, while edges represent interactions or relationships.

2. GNN Model:
   A Graph Neural Network is trained on the graph to learn embeddings for users and movies.
   The model uses message passing to propagate information across the graph, capturing complex relationships.

3. Recommendation Generation:
   The learned embeddings are used to predict user preferences and generate personalized movie recommendations.

@@@ Dataset we have built :
We scraped the rotten tomato data to get the user sentiments along with user reviews for about 10k data. we cleaned those data to get around roughly 9k data with proper data i.e movie title, sypnosis, overview of the movie along with other information like movie average ratings, movie director, producer,cast info.We again scraped the user reviews about the scraped movies data i.e every single user reviews on every single movie that we scraped above. then we cleaned those reviews of the users to get the data.We used TMDB 1M movie dataset to get additional innformation about the movie meta-data
