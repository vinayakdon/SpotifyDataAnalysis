### 🎧 Spotify Music Data Analysis
A Decision Support System Project using EDA and Machine Learning

### 📘 Overview
This project presents a comprehensive analysis of Spotify music data to support strategic decision-making in the music industry. Developed as part of the Decision Support System (DSS) course, it demonstrates how data science and machine learning techniques can be applied to understand music trends, audience preferences, and optimize content strategies on streaming platforms.

### 📊 Project Objectives
Perform Exploratory Data Analysis (EDA) on track and artist data

Uncover trends in audio features, popularity, and listener behavior

Build machine learning models (KMeans, KNN) for:

Music style clustering

Personalized music recommendation

Provide data-driven insights and recommendations for producers, curators, and marketers

### 🧾 Dataset
The dataset was sourced from Kaggle and includes:

tracks.csv: Audio features and metadata of Spotify tracks
artists.csv: Artist-level metadata including popularity and followers

Both the dataset are too large so not able to provide the file here, so you can find it on kaggle

➡️ These files were merged using the artist ID to create a unified dataset for analysis.

### 🛠️ Technologies Used
Python (Jupyter Notebook)

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

### 📈 Key Analyses & Insights
Popularity Trends: Most tracks have low popularity; a few dominate streams (long-tail effect).

Feature Correlation: Energy and danceability moderately correlate with track popularity.

Explicit Content: Slightly higher popularity, especially in hip-hop/pop genres.

Temporal Evolution:

Popularity, danceability, and energy have increased since 2000

Track releases have grown exponentially in the digital era

Artist Influence: Follower count is a strong proxy for consistent popularity

### 🤖 Machine Learning Models
KMeans Clustering
Groups songs into stylistic clusters based on audio features (energy, danceability, etc.)

KNN Recommendation System
Suggests tracks based on input preferences for:

Danceability

Energy

Release year

Artist followers

📌 Use Case Applications
Playlist curation and personalization

Strategic song production based on popular features

Artist development and marketing

Data-driven decision support for streaming platforms
