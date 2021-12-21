# spotify_mlproject
This project has been developed during the Machine Learning course at the Science Faculty of Lisbon University (FCUL). The dataset analyzed is '*Spotify_dataset.csv*'. This dataset, downloaded from Kaggle, contains selected data from the following dataset: Hit Predictor. 

The 'Spotify_dataset.csv' we learned from has 41 106 instances described by 20 data fields.

The project work can be divided into:
- **Task 0 (Know your Data) - Exploratory Data Analysis**: in this section we explored if there are missing values, outliers and we made changes in our initial data. We also explored the features and analysis the correlation between quantitative variables.

- **Task 1 (Supervised Learning) - Predicting Hit or Flop and Discrete Valence**.
In this task we applied 2 classification tasks: binary classification task, where the target variable is `hit`; multiclass classification, where the target variable is `DISCRETE_VALENCE`.
For both the binary and the multiclass classification we used at least 1 classifier for each of these categories: Tree model, Linear model, Distance-based model and Naive Bayes model. We used cross-validation to evaluate the results.

- **Task 2 (Unsupervised Learning) - Characterizing Tracks**: In this task we used unsupervised learning algorithms for characterizing the tracks.
  * **Association rule mining** to find associations between the features and the target hit/discrete valence.
  * **Clustering algorithms** to find similar groups of tracks.
