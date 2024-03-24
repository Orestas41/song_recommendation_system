<h1 align='center'>Spotify Song Recommendation System</h1>
<h3 align='center'>Orestas Dulinskas</h3>
<h4 align='center'>March 2024</h4>

## Background

With the exponential growth of music streaming platforms, users often face the challenge of discovering new songs tailored to their preferences. By leveraging machine learning techniques, this project seeks to address this issue by creating a personalized recommendation system. The dataset includes various features such as track name, artist, genre, and musical attributes like danceability, energy, and tempo. Through K-means clustering, songs with similar characteristics will be grouped together, allowing users to explore and discover music that aligns with their tastes.

## Objective

The objective of this project is to develop a robust and effective song recommendation system using K-means clustering with Spotify data. The goal is to cluster songs based on their musical attributes, such as danceability, energy, and acousticness, in order to group similar songs together. This clustering approach will enable the creation of tailored recommendations, allowing users to explore new music that closely matches their preferences and tastes. Ultimately, the objective is to enhance user satisfaction and engagement by providing accurate and relevant song suggestions, thereby improving the overall music listening experience for users.

## Data

The Spotify dataset consists of various attributes related to songs, artists, and musical characteristics. Here is a brief description of each column:

* **track_name**: The name of the song.
* **artists**: The name of the artist(s) who performed the song.
* **artist_genres**: The genres associated with the artist(s).
* **explicit**: A binary indicator (0 or 1) indicating whether the song contains explicit content.
* **album_name**: The name of the album to which the song belongs.
* **release_year**: The year in which the song was released.
* **danceability**: A measure of how suitable a track is for dancing, ranging from 0 to 1.
* **energy**: Represents the intensity and activity of the song, ranging from 0 to 1.
* **key**: The key the track is in (e.g., C, D, E, etc.).
* **loudness**: The overall loudness of the track in decibels (dB).
* **mode**: Indicates whether the track is in major (1) or minor (0) key.
* **speechiness**: Detects the presence of spoken words in the song, ranging from 0 to 1.
* **acousticness**: Represents the likelihood of the song being acoustic, ranging from 0 to 1.
* **instrumentalness**: Indicates the likelihood of the song containing no vocals, ranging from 0 to 1.
* **liveness**: Measures the presence of a live audience in the recording, ranging from 0 to 1.
* **valence**: Describes the musical positiveness conveyed by a track, ranging from 0 to 1.
* **tempo**: The overall estimated tempo of the track in beats per minute (BPM).
* **time_signature**: Represents the number of beats in each bar of the song's music.

This dataset provides a comprehensive overview of songs and their characteristics, which will be utilized to build an efficient song recommendation system using K-means clustering.

## Spotipy

Spotipy is a lightweight Python library for the Spotify Web API. It provides an easy way to interact with Spotify’s music data and features programmatically.

Getting started:

* To use Spotipy, you’ll need to create an app on the Spotify Developer Dashboard and obtain your app’s client ID and client secret. Follow these instructions: https://developer.spotify.com/documentation/web-api/tutorials/getting-started
* Set client ID and client secret as Secrets on Kaggle. Follow these instructions: https://www.kaggle.com/discussions/product-feedback/114053

Now you are able to use Spotipy. Check official docummentaion for more information: https://spotipy.readthedocs.io/en/2.22.1/
