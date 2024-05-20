# MusicRecommendation

## Overview
This project is a Music Recommendation System developed in Python using a Jupyter Notebook. It recommends songs from a database based on provided attributes such as duration, explicit content, popularity, and various musical characteristics like happiness, acousticness, danceability, energy, instrumentalness, loudness, and tempo. The recommendations are generated using a soft set-based approach.
Dataset: [Kaggle](https://www.kaggle.com/datasets/vatsalmavani/spotify-dataset/data) 

## Example 
IN: 
```python
song1 = {"duration_ms": 2, "explicit": 1, "popularity": 1, "happiness": 9, "acousticness": 3,
         "danceability": 2, "energy": 4, "instrumentalness": 7, "loudness": 5, "tempo": 2}
```
OUT: ['Henry Mancini'], Shades Of Sennett

## Future plans
I plan to enhance the Music Recommendation System by implementing song recommendations based on other provided songs using the K-means clustering algorithm.
