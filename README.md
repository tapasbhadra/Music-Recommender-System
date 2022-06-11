# Music-Recommender-System

Introduction:
Recommender systems are being used by every major online platform to personalize the experience of their users. I have created a song recommender system which will understand and analyze audio features. The model will then recommend 10 songs based on my playlist and liked songs

Data:
I have used the Spotify API for Python called Spotipy to extract features of the songs in the playlists. 6 Spotify playlists of different genres were used to build the database. The playlists encompass the following the genres:
1. Jazz
2. Rock
Punk Rock
R&B
Pop
Electro Swing

The playlist URL of the selected Spotify playlists were used to extract their URIs. URI is a unique id for eac playlist. In addition, each song has a unique track_URI which will be used to extract the song features.
For this analysis, I have used song and artist features as below:
track_name
artist_uri
artist_info
artist_name
artist_pop: Popularity of the artist
artist_genres
album
track_pop: Popularity of the track
The above features describe the song and the artists. Additionally, descriptive features of the song which detail the coherent elements of the track have been extracted. There are as follows:
acousticness
danceability
energy
instrumentalness
liveness
loudness
speechiness
tempo
time_signature
