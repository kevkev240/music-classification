# Music Classification
CS 534 Fall 2022 Project

# Data
The original data GTZAN can be found on [Kaggle](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)
Preproccesed data are not included because they are too large. However, they can be reprodeuced using part of the code in ./notebooks/preprocessing.ipynb and the raw audio files in ./data/genres_original.

# Notebooks
lstm.ipynb contains the code for running baseline LSTM models. 
lstm_tuning.ipynb tries feature expansion. 
bilstm.ipynb experiment with biLSTM. 
classification_csvdata.ipynb explored the CSV data in ./data/features_3_sec.csv.
