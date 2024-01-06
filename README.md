## Spotify song popularity predictor case study

A case study that identifies that popularities of a song per genre using regression models such as `linear regresion`, `logistic regression`, and `neural networks`. It uses the spotify music dataset that is composed of 17,996 songs and has the following attributes. The hyperparameters were tuned by using grid search, thus increasing the performance of said models.

## Track Features

`Artist Name` – name of artist

`Track Name` – name of song

`Popularity` - value ranging from 0 to 100, with 100 being the most popular. It is determined by an algorithm and it takes into account the total plays and recentness.

`danceability` – determines a song's dance suitability by taking into account a number of musical elements, such as tempo, beat intensity, rhythm stability, and overall regularity. A score of 0.0 indicates low danceability, while 1.0 signifies high danceability.

`energy` – value ranging from 0.0 to 1.0 and represents a perceptual measure of intensity and
activity. Energetic tracks, characterized by speed, loudness, and noise, tend to score high. Perceptual features contributing to this assessment include dynamic range, perceived loudness, timbre, onset rate, and general entropy.

`key` – indicates the track's key. Standard Pitch Class notation is used to convert numbers to pitches. If there is no key, the value is set to -1.

`loudness` – value in decibels (dB) representing a track's overall loudness. Usually, values fall between -60 and 0 dB.

`mode` – represented as  either 1 for major or 0 for minor, which refers to the scale from which melodic content it originates.

`speechiness` – measures the amount of spoken words in a track, where values below 0.33 more likely indicates non-speech-like tracks, values between 0.33 and 0.66 suggests tracks may include both music and speech, and values between 0.66 and 0.33 indicate recordings primarily composed of spoken content.

`acousticness` – value ranging from 0.0 to 1.0 of whether the track is acoustic. Higher values
indicate higher confidence that it is acoustic.

`instrumentalness` – value ranging from 0.0 to 1.0 which predicts whether or not a track includes vocals, considering the "ooh" and "aah" noises as instrumental. Values above 0.5 suggest increasing confidence in the absence of voice elements, while values closer to 1.0 imply a larger possibility that the track is instrumental.

`liveness` – detects the presence of an audience in a recording wherein larger values suggest a higher chance of a live performance.

`valence` – value ranging from 0.0 to 1.0 represents the degree of the music's positivity, where higher values denote a more upbeat and joyful tone and lower values, a more sad and serious mood.

`tempo` – refers to the overall estimated speed or pace of a track, which is expressed in beats per minute (BPM), that is derived directly from the average beat duration.

`duration_in min/ms` – duration in ms

`time_signature` – value ranging from 3 to 7, indicating the estimated time signature. A notational convention used to identify the number of beats in each bar or measure.

`Class` – genre of the track
