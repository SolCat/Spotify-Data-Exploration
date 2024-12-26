## **Project Overview**
This project, part of my Data Mining course, applies various concepts learned, from data preparation to predictive model evaluation. The dataset focuses on music data scraped from the Spot On Track website.

## **Data & Statistics**
The dataset is scraped from **Spot On Track**, which collects Spotify data, and consists of two files:

- **playlists.data**: Contains information about the composition of five playlists.
- **tracks.data**: Describes songs in the playlists using 10 Spotify-calculated variables:
  - **BPM**: Beats per minute, indicating the tempo.
  - **Key**: Tonality of the track.
  - **Mode**: Major or minor scale.
  - **Danceability**: Suitability for dancing.
  - **Valence**: Musical positivity.
  - **Energy**: Intensity and activity level.
  - **Acousticness**: Likelihood the track is acoustic.
  - **Instrumentalness**: Likelihood the track is instrumental.
  - **Liveness**: Likelihood the track is performed live.
  - **Speechiness**: Likelihood the track contains spoken words.

## **Methodology**
We will perform three different analyses:

1. **Exploratory Analysis**: This includes descriptive statistics (1D, 2D), such as histograms, boxplots, and scatter plots, to explore the variables. We'll also analyze the average song profile for each playlist and track changes in rankings.
2. **Multidimensional Exploratory Analysis**: Using dimensionality reduction methods like PCA, tSNE, and MDS, we will project the songs in a 2D space to interpret relationships and identify outliers.
3. **Predictive Analysis**: We'll build models to predict playlist membership or song rankings based on the 10 variables and assess model performance.

