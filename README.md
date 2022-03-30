
[![Python](https://img.shields.io/badge/Python-3.9-orange)](https://www.python.org/downloads/release/python-390/)  [![Frontend](https://img.shields.io/badge/Frontend-Stremlit-green)](https://streamlit.io) [![AI](https://img.shields.io/badge/API-TMDB-yellow)](https://www.themoviedb.org/documentation/api) [![Model](https://img.shields.io/badge/Model-Cosine%20Similarity-red)](https://www.sciencedirect.com/topics/computer-science/cosine-similarity)


# Movie Recommender System using Streamlit and Cosine Similarity

A content-based recommendation system that recommends films 
similar to the selected film user.

The model is based on cosine similarity which is metric used 
to determine how similar the documents are irrespective of
their size.

The frontend is made using Streamlit and the API used to get the movie is TMDB, https://www.themoviedb.org/documentation/api
using iMDB Id call the API for the movie information.

## Screenshots of webapp

![App Screenshot](https://github.com/Equinox0606/Movie-Recommender-System/blob/b5a8c66ecb09c68aa11273e648c4543067c58bf8/Images/Opera%20Snapshot_2022-03-30_235305_localhost.png?raw=true)


![App Screenshot](https://github.com/Equinox0606/Movie-Recommender-System/blob/main/Images/Opera%20Snapshot_2022-03-30_235142_localhost.png?raw=true)




## How does it figure out similar movies?

How can a it decide which movie is similar to the one we have selected?
Here comes similarity score

The similarity score is a number between 0 and 1 that represents 
how similar two things are. This is accomplished by contrasting 
their details adjacent to one another. This is accomplished by
 cosine similarity.

## What is Cosine similarity

Cosine similarity is a metric used to measure how similar the
 documents are irrespective of their size. Mathematically, 
 it measures the cosine of the angle between two vectors 
 projected in a multi-dimensional space.

![App Screenshot](https://github.com/Equinox0606/Movie-Recommender-System/blob/main/Images/Opera%20Snapshot_2022-03-31_001642_www.sciencedirect.com.png?raw=true)

## Why cosine similarity for our use case

The cosine similarity is advantageous because even if the two
 similar documents are far apart by the Euclidean distance 
 (due to the size of the document), chances are they may still 
 be oriented closer together in a multi dimensional space. The 
 smaller the angle, higher the cosine similarity.

![App Screenshot](https://github.com/Equinox0606/Movie-Recommender-System/blob/main/Images/2b4a7a82-ad4c-4b2a-b808-e423a334de6f.png?raw=true)

Raed more about Cosine similarity - [[Link](https://www.sciencedirect.com/topics/computer-science/cosine-similarity)] [[Link2](https://www.machinelearningplus.com/nlp/cosine-similarity/)]
## Dataset Used for the Model

[Dataset - IMDB Dataset (kaggle)](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

