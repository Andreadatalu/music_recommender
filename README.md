# Music recommender: Bootcamp individual project

## Overview

This task is one of the weekly projects that we complete. It was created as part of an individual project where the goal was to create a music recommender using a user-selected starting input.

**The following abilities are employed in this project:**

+ Web scraping on the top 100 songs currently on the website to create the inicial dataset
+ Using an API to get more songs for the database using the Spotify API to web scrape a large playlist and increase the database
+ Working with the cluster method to define categories of songs
+ Using the spotify API to encode the input and being able to recommend a song that is in the same cluster.

## Approach

In the project, a combination of functions was developed so that the output was the recommendation of a song that is in the top 100 or in our base of songs that share the same cluster, obtained through the variables found in the spotify uri.

**Function understanding**
+ Receive the user's input
+ Search the song to see if it's in the top 100; if it's in the top 100, it's recommending a new song from the top 100
+ **If the song is not in the top 100** so, connect to the Spotify API to get the features
+ Do the process to classify the song in a cluster
+ **If it finds a cluster,**  it's recommending a new song, **if not** it displays y a sorry message - Try y again.

## Repository structure

