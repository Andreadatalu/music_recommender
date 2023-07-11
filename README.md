# Music recommender: Bootcamp individual project

## Overview

This task is one of the weekly projects that we complete. It was created as part of an individual project where the goal was to create a music recommender using a user-selected starting input.

**The following abilities are employed in this project:**

+ Web scraping on the top 100 songs currently on the website to create the initial dataset
+ Using an API to get more songs for the database: using the Spotify API to web scrape a large playlist and increase the database
+ Working with the cluster method to define categories of songs
+ Using the Spotify API to encode the input and being able to recommend a song that is in the same cluster.

## Approach

In the project, a combination of functions was developed so that the output was the recommendation of a song that is in the top 100 or in our base of songs that share the same cluster, obtained through the variables found in the Spotify uri.

**Function understanding**
+ Receive the user's input
+ Search the song to see if it's in the top 100; if it's in the top 100, it's recommending a new song from the top 100
+ **If the song is not in the top 100** so, connect to the Spotify API to get the features
+ Do the process to classify the song in a cluster
+ **If it finds a cluster,**  it's recommending a new song, **if not** it displays a sorry message - Try y again.

## Repository structure

+ Music_recommender_process_1_and_2: This file describes the process of creating the Top 100 database by web scraping the web page popvortex.com, using BeautifulSoup
+ Process_part_3: In this document we make the connection to the spotify credentials to scrape a playlist to make the database that includes the features to be used for clustering.
+ Process_part_4_cluster: We use K Means to divide our database into clusters.
+ Process_part_5: Here is the whole process to recommend a song, if it's not in our top 100 database, it will be scraped that specific song to give it a cluster and recommend a song from the same cluster randomly.

**Final database used:**
+ music_100.csv
+ Final_playlist.csv
 
## Contributes and support
I hope you enjoy this project like I did, and put these skills into practice. My name is Andrea Luna, and I appreciate you choosing to learn with me. Please get in touch with me if you have any queries, remarks, or ideas. You are also welcome to play around with the data to gain further insights.

**Join my network on LinkedIn:** andrea-luna/ or https://www.linkedin.com/in/andrea-luna-/
