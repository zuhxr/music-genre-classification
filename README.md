# Music Genre Classification using GTZAN Dataset

## Project Overview
This project uses the GTZAN dataset to classify music into 10 different genres.The approach taken is a **feature-based** machine learning model, which leverages pre-extracted audio features (such as MFCCs, chroma, tempo, spectral properties, etc.). We trained the model using a **Random Forest Classifier** to predict the genre of a song based on these extracted features.

## Dataset Description
The dataset includes:
- **Genres**: 10 genres, 100 audio files each (30 seconds).
- **CSV Files**: Pre-extracted features from the audio files.
  - `features_30_sec.csv`: Features extracted from 30-second audio clips.
  - `features_3_sec.csv`: Features extracted from 3-second audio clips (for future extensions).