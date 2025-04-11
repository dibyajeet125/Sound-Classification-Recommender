# Sound-Classification-Recommender
Developed a sound classification and recommender system using a dataset of 10 genres, achieving a classification accuracy of 90.09% with XGBoost and providing personalized recommendations based on cosine similarity. The system analyzed 57 audio features across 1000 tracks.


This project involves the development of a robust sound classification system and a music recommender system. The classification model is trained on a dataset of audio features extracted from 1000 tracks across 10 genres (blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, rock). The recommender system uses cosine similarity to suggest tracks with similar acoustic properties.

Key Components:

Data Preparation:

Dataset: 1000 audio tracks across 10 genres.

Features: 57 audio features including chroma, spectral centroid, bandwidth, and Mel Frequency Cepstral Coefficients (MFCCs).

Classification Model:

Models Evaluated: Naive Bayes, Stochastic Gradient Descent, KNN, Decision Trees, Random Forest, SVM, Logistic Regression, Neural Networks, and XGBoost.

Best Model: XGBoost achieved the highest accuracy of 90.09%.

Feature Importance:

Method: Permutation importance was used to evaluate feature contributions.

Top Features: perceptr_var, perceptr_mean, mfcc4_mean, chroma_stft_mean, and harmony_mean were identified as the most impactful.

Recommender System:

Method: Cosine similarity was used to compute similarities between audio tracks.

Example: For a given track like "pop.00003.wav", recommendations included tracks from diverse genres such as "country.00044.wav", "reggae.00093.wav", "hiphop.00043.wav", "hiphop.00059.wav", and "reggae.00053.wav".


This project demonstrates the application of machine learning in sound classification and music recommendation, showcasing the potential of these techniques in enhancing audio analysis and recommendation systems.

DATASET LINK: https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification
