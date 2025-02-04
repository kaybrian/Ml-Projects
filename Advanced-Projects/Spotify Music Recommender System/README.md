Spotify uses AI to recommend music to its users. You can try building a recommender system based on publicly available data on Spotify.

Spotify has an API that you can use to retrieve audio data — you can find features like the year of release, key, popularity, and artist. To access this API in Python, you can use a library called Spotipy.

You can also use the Spotify dataset on Kaggle that has around 600K rows. Using these datasets, you can suggest the best alternative to each user’s favorite musician. You can also come up with song recommendations based on the content and genre preferred by each user.

This recommender system can be built using K-Means clustering — similar data points will be grouped. You can recommend songs with a minimal intra-cluster distance between them to the end-user.

Once you have built the recommender system, you can also turn it into a simple Python app and deploy it. You can get users to enter their favourite songs on Spotify, then display your model recommendations on the screen that have the highest similarity to the songs they enjoyed.

Dataset: (Kaggle Spotify Dataset)[https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks]