# Classifying Insincere Questions on Quora

Requirements
------------------
For python, the following packages should be installed
- numpy
- keras
- pandas
- sckikit-learn
- matplotlib
- nltk

Preliminary Data Analysis
-------------------------
For preliminary data analysis, run Demo_AnalyzingData.ipynb. The file requires train
and test data csv files, which are available at https://www.kaggle.com/c/quora-insincere-questions-classification. Download these files and place them in the current directory
inside a folder named "input".

The Demo_AnalyzingData.ipynb file preprocesses the data, analyzes the common words associated with insincere questions, and builds a simple baseline model for classification of insincere questions on Quora.

Classification Model - A
------------------------
To build a classification model, run Demo_Classification.ipynb. The file requires Global Vector (GloVe) embeddings, that can be downloaded from https://www.kaggle.com/c/quora-insincere-questions-classification. The downloaded embeddings should be placed in the current directory inside a folder named "embeddings".

The Demo_Classification.ipynb file preprocesses the data, computes the Global Vector (GloVe) embeddings, and then uses the embeddings to train a Bi-directional LSTM neural network for Insincere Questions Classification.
