# Unsupervised ML - Netflix Movies and TV Shows Clustering

This dataset consists of tv shows and movies available on Netflix as of 2021. The dataset is collected from Flixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

## <b>In this  project, we are required to do </b>
1. Exploratory Data Analysis
2. Understanding what type content is available in different countries
3. Is Netflix has increasingly focusing on TV rather than movies in recent years.
4. Clustering similar content by matching text-based features

# We got following conclusions from this project:

1. There is about 30.95% TV shows and 69.05% Movies in the dataset.
2. Recently, more Movies are getting released as compared to TV Shows.
3. USA has the highest number of content in both categories, Movies and Tv shows.
4. TV-MA rated movies are most popular.
5. Top 3 content genres are International movies, dramas, comedies.
6. Anupan Kher acted in most number of Movies.
7. Most movies have duration around 90 minutes.
8. Most TV Shows have 1 Season.
9. More shows gets released during winter months.
10. For text processing we performed following steps:
     - Expand Contraction
     - Lower Caseing
     - Removing punctuations, Stopwords, URLs, white spaces etc.
     - Lemmatzation
     - Tokenization
     - TF-IDF vectorization
     - Dimentionality Reduction (to 3000 components)
11. Trained two clustering models:
     - KMeans Clustering (17 clusters) with Silhouette score 0.0125
     - Hierarchical Clustering (15 clusters) with Silhouette score 0.006
12. Using this data, a Content based recommendation system was created using cosine similarity, which provided recommendations for Movies and TV shows.

