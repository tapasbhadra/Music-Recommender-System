# Music-Recommender-System

# Introduction:
Recommender systems are being used by every major online platform to personalize the experience of their users. I have created a song recommender system which will understand and analyze audio features. The model will then recommend 10 songs based on my playlist and liked songs

# Data:
I have used the Spotify API for Python called Spotipy to extract features of the songs in the playlists. 6 Spotify playlists of different genres were used to build the database. The playlists encompass the following the genres:
1. Jazz
2. Rock
3. Punk Rock
4. R&B
5. Pop
6. Electro Swing

# Features
The playlist URL of the selected Spotify playlists were used to extract their URIs. URI is a unique id for eac playlist. In addition, each song has a unique track_URI which will be used to extract the song features.
For this analysis, I have used song and artist features as below:
1. track_name
2. artist_uri
3. artist_info
4. artist_name
5. artist_pop: Popularity of the artist
6. artist_genres
7. album
8. track_pop: Popularity of the track

The above features describe the song and the artists. Additionally, descriptive features of the song which detail the coherent elements of the track have been extracted. There are as follows:
1. acousticness
2. danceability
3. energy
4. instrumentalness
5. liveness
6. loudness
7. speechiness
8. tempo
9. time_signature

# Model
I have developed a Content Based Recommender System that uses cosine similarity between the data and my personal playlist that I have extracted using the Spotify API. The top 10 tracks having the highest similarity are recommended.

