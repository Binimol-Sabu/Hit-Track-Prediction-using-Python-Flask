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

Source: [[Spotify Web API](https://developer.spotify.com/documentation/web-api/)](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset)

## Render

[![PythonAnywhere](https://img.shields.io/badge/PythonAnywhere-Live%20Demo-blue)](https://binimol.pythonanywhere.com/)

The application is hosted on PythonAnywhere:
- **Web Server**: Flask with WSGI configuration
- **Always-on**: Keeps the app running 24/7
- **HTTPS**: Secure connections enabled
- **Free Tier**: Suitable for small-to-medium traffic

Access the live prediction tool:  
[binimol.pythonanywhere.com](https://binimol.pythonanywhere.com/)
