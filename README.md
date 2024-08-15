# KaggleSpotify6K
Data from https://www.kaggle.com/datasets/viktoriiashkurenko/278k-spotify-songs 

This project will be using various AWS services (EC2, S3, EMR) to load in a large dataset (~100 GB) and generate a song/playlist recommendation system using PySpark. 

Song data (from the original dataset and additional data) was sourced from the Spotify API.

The main algorithm used in the recommendation system was the Dimension Independent Matrix Square using MapReduce (DIMSUM) algorithm.

Main Libraries Used: Pandas, PySpark, NLTK, Boto3
