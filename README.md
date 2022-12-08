# Spotify-API-Repo

Hello World!

In here I have included my Python code and documentation for my recent blog posts.

I have also included my EPA (Exploratory Data Analysis) python documentation! Hopefully this can allow you to follow along my work for creating visuals!

And finally, I have added the complete documunted python notebook to my most recent blog post.

The data was pulled from Spotify using their API. https://developer.spotify.com/documentation/web-api/


The table included has basic information about each song in the playlist. It also has information such as danceability, speechiness, and energy. This are variables created by Spotify used to create a deeper understanding of each song. It will be useful in further exploratory data analysis. Down below are definitions for the audio features that I used.

Danceability: “How suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.”

Energy: “A measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy.”

Loudness: “The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Values typically range between -60 and 0 db.”

Speechiness: “Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks.”

Instrumentalness: “Predicts whether a track contains no vocals. The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0.”

Liveness: “Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live.”

Valence: “A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).”

Tempo: “The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.”

Popularity: A value calculated using the frequency of listens in comparisons to other songs from 0 - 100.

Duration: Length of track in seconds.



The "greatest_hits_ever.csv" includes a table of the final dataset that I created.

The "Spotify Scraping Code.ipynb" includes all of my python code from this project, it excludes my own person API keys.

The "Spotify EPA Documentation.ipynb" includes all code for creating visuals.

The "Greatest Hits Analysis Code.ipynb" includes all code for creating the audio feature visual.
