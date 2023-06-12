# Introduction
In this project, I will focus on Topic Modeling and Text Clustering. When I began exploring about NLP, these two terms seemed similar to me. However, I figured out that they are completely different. Therefore, I will apply two techniques on dataset Spotify million songs from Kaggle. This dataset can be found here:https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset. The dataset contains more than 50000 song with four features: the artist name, the song's name, the link and the lyrics of that song.

The main purpose of my project is to define the song's genre based on their lyrics. This is the unsupervised learning task, since we do not know anything about the type of song. Hence, my idea is to apply machine learning techniques to assign each song to different groups that contain the similar song. To do this, I use two methods: K-means and LDA topic modeling in the project. Before applying the machine learning methods, we need to convert the lyric text into numeric data. First of all, the most important step is text mining, where we clean the lyric text.
## Text clustering
In clustering, I apply k-means to partition song dataset into 9 groups. However, the results are not good since there were many overlappings.
## Topic modeling
It works better in defining the groups of each song, and by applying T-SNE or UMAP, we could see the clear separation between each topic group.
