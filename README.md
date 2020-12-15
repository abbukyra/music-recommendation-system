# Music Recommendation System
## Project Description and Goals
Music reflects an individual’s personality. Music can change an individual’s mood, fuel excitement, or provide calmness and relaxation. Most importantly, music connects people from all walks of life and is a conversation starter. However, there is an endless amount of music. Songs are constantly created and released which may hinder an individual to discover more music and stick to the ones they are familiar with. This limits human connection through music. Our project hopes to keep the human connection, build new relationships, and become the bridge that connects different worlds through music. Our approach is in creating a system that allows a user to provide a playlist they love then we examine each song in a playlist, the system looks for a similar song that belongs to another individual’s playlist to recommend to the user. Since a major part of determining relationships between songs is genre, our approach is to assure accuracy of a song’s genre by implementing a decision tree and a multinomial logistic regression classifier to predict the genre. Afterwards, we implemented a K-d tree as our main algorithm in creating a music recommendation system.
Given our approach, our goal is to recommend a playlist to the user with songs that do not already exist in their current playlist. Through our system, we can foster building new relationships and giving individuals a conversation starter which is music.

## Team Members 
Tracey Kong, Donald Chen, Kyra Alyssa Abbu

## HOW TO RUN

### Music Recommendation System (Main)
1. Open music-recommendation-system/KDTree/KDtreeRecommender.ipynb.
2. Within KDtreeRecommender.ipynb, you can input the name of the playlist.

#### [?] If you are interested in running the genre classifiers (decision tree and multinomial logistic regression), you can go to music-recommendation-system/data_setup/ 
1. LabelingAndFiltering.ipynb = Decision Tree
2. Multinomial Logistic Regression.ipynb = Multinomial

## Presentation Slides
https://docs.google.com/presentation/d/1Pcto_mbZG3BP8lSn-p_763Ra9xM09wFHHqwWDKoFGxk/edit?usp=sharing
