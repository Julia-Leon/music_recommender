# music_recommender

##Business goal and short summarise:
We are presenting to GNOD a project for a new music recommendator, not only for bands, as they already have in Gnoosic, but also for songs for their users. The idea is to give users 2 new possibilities when searching for recommendations: songs that are similar to the ones they picked from an acoustic point of view, and songs that are popular around the world right now independently from their tastes.

We are going to use API from Spotify to collect as much data as possible. Once the data is collected, we want to create clusters of songs that are similar to each other. Finally, we are building a tool that will take a song as an input from the user, this song will match with one of the clusters we created, and the tool will prioritize giving the user an output recommendation of a song from that same cluster.

In order to start, we want to explore and we are going to directly scrape the web and get a few hundreds from an online site and see if we can apply process with a small sample.

So here we go scraping a first shot of hot songs from Billboard.
