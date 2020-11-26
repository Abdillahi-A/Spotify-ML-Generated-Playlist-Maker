# Spotify-ML-Generated-Playlist-Maker

## About:
This project uses unsupervised learning learning (K-means Clustering) to organise my favourite tunes into four ML generated playlists based on song attributes such as danceability, valance, energy and more.

This project is divided into 3 parts.

## Part 1: Data Exploration
This part starts bt loading my listening data over the past year and performing some exploaratory data analysis in order to get a feel of my listening habbits and learn some insights into my music taste e.g.

**Who are my Top 50 Streamed Artists?**
![Top 50 Artists](https://github.com/Abdillahi-A/Spotify-ML-Generated-Playlist-Maker/blob/main/top50artists.png)


**Do I listen to more music on weekends vs weekdays?**
![Music by Day of Week](https://github.com/Abdillahi-A/Spotify-ML-Generated-Playlist-Maker/blob/main/hoursplayedbydayofweek.png)

**What months do I listen to the most music?**
![Music by Month](https://github.com/Abdillahi-A/Spotify-ML-Generated-Playlist-Maker/blob/main/musicbymonth.png)

**Do I listen to the same songs repeatedly?**
![Histogram Of MinsPlayed](https://github.com/Abdillahi-A/Spotify-ML-Generated-Playlist-Maker/blob/main/minutesPlayedHistogram.png)



## Part 2. Access Spotify API 

The streaming data used in the data exploration doesn't include addtitional attributes about the tracks e.g. tempo, loudness etc. This is because spotify expects us to request these features. Thus, to get this information we are going to need to access the spotify API. Part two tackles this.

## Part 3. Implement K-Means Cluster and Principal Component Analysis (PCA)
The aim of this project is to use K-Means clustering to organise my favourite songs and cluster them into playlists of simialr songs. To determine the optimal number of clusters to use, the elbow method is employed. K=4 was chosen as the number of clusters to go for. PCA was used to reduce the dimension of our data from a high dimensional space, to a lower 2d space, where we can visualise relationships between clusters.

**Elbow Method**

![Elbow Method](https://github.com/Abdillahi-A/Spotify-ML-Generated-Playlist-Maker/blob/main/elbow_method.png)

**PCA**

![PCA](https://github.com/Abdillahi-A/Spotify-ML-Generated-Playlist-Maker/blob/main/pca.png)


## Results:

1. cluster 0 - more chill, mellow vibes (mostly hip hop and RnB and some slow indie). See full playlist here: https://open.spotify.com/playlist/3yqWnqqJDuoAjk958MonNd?si=yA9Cvo72TIWFZUhTtUisUw

2. cluster 1  - more upbeat songs to dance or workout to. See full playlist here:
https://open.spotify.com/playlist/2zWLRuc8S54vWSLVQMTxwt?si=HdtLttj0QYOWZyyFTyNlAA

3. cluster 2 - very high energy electronic/house/techno songs. See full playlist here:
https://open.spotify.com/playlist/3CR7D3pBPrIeEcvRS0RGi2?si=0Y3Vpp8-TX2Eqe3LDebrRw


4. cluster 3 - most distinct group, mainly categorised by pianos, inspirational movie scores, string orchestra, and a more melancholy vibe. These are songs I’d likely study to. See full playlist here:
https://open.spotify.com/playlist/0CHQKJMJIz9WK7RcXJKw8h?si=k_ECFVskS6WkAsdJDJOGUA









