# Introduction
![bass-guitar](https://github.com/JaviSandoval94/Proyecto-1-Spotify/blob/master/pexels-freestocksorg-96380.jpg)
We are a consulting company for independent artists. We are helping a new Mexican artist to launch their next hit in Mexico and Latin America, which is planned to be released in last quarter 2020 in the Spotify platform, to remain in the Top 50 Chart throughout the next year.

## Tasks:
1) Identify most popular music genres in the population segment that the artist is targeting.
2) Identify patterns in the tempo, energy, danceability and acousticness of the music that people in that segment listen to in different quarters.
3) Define the properties that the artist's song should have to be succesful in last quarter 2020 in Mexico and Latin America.
4) Predict how popular this song will be in upcoming quarters.

## Hypothesis:
If we determine the optimal mix of the variables related to a successful song in Mexico, then we can help the artist release a successful song in the last quarter of 2020:
  1) If the tempo of a song is higher than 100 bpm, then it will be more popular.
  2) If the artist chooses to release a reggaeton song, then it will remain in the Top 50 Chart throughout the next year.
  3) If a song has a higher level of energy, then it will be more likely to be in the Top 50 throughout the next year.
  4) If a song has a higher level of danceability, then it will be more likely to be in the Top 50 throughout the next year.

# Data sets
All of our data sets come from the Spotify API and are saved in `.xlsx` and `.tsv` formats. All of the files are available in this repository and are the following:
* `chartmx_03_20.xlsx`: Artist and release information for the Top 50 Chart Songs from 2017 to 2019.
* `audiofmx.xlsx`: Stats related to the individual songs, including `acousticness`, `danceability`, `duration_ms`, `energy`, `instrumentalness`, `key`, `liveness`, `loudness`, `mode`, `speechiness`, and `tempo`.
* `songDb.tsv`: Song genres

# Code description
The analysis is done using Pandas and Matplotlib in Jupyter Notebook. The code containing our analysis can be read in the `Project1-Spotify-FinalReport.ipynb` file. There is also a presentation as a summary to our findings in the `Proyecto-1-Spotify.pdf` file.

# Next steps
The analyses presented in this project are helpful to know preliminary information about music popularity in Mexico from 2017 to 2019. However, this information is presented in a static report. Next steps for the project include further statistical analysis of the data to extract more insights and make predictions for the following year. There is also an opportunity to automate the report in an online visualization which could call an API directly to return updated data every time it is called.
