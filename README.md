# Spotify Hit Prediction

Flask web application that predicts song popularity and classifies tracks as "Hit" or "Non-Hit" using machine learning.

## About
This project analyzes Spotify track metadata using Random Forest Classification to predict a song's popularity. Users can input track features via a web interface to get predictions.

## Dataset
The dataset contains:
- Track ID
- Acousticness
- Danceability
- Energy
- Instrumentalness
- Key
- Liveness
- Loudness
- Speechiness
- Tempo
- Valence
- Popularity (target variable, 0-100)

Source: [Spotify Web API](https://developer.spotify.com/documentation/web-api/)

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/Binimol-Sabu/Hit-Track-Prediction-using-Python-Flask.git
