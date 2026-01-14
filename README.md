## NCA
A comprehensive data analysis, clustering, and content-based recommendation system built on the Netflix Titles dataset using Python, NLP, and Machine Learning techniques.

# Project Objectives-
Perform Exploratory Data Analysis (EDA) on Netflix content
Clean and engineer features from raw metadata
Apply Natural Language Processing (NLP) on titles and descriptions
Cluster content using TF-IDF + KMeans
Build:
A basic content-based recommender
An improved hybrid recommender using text, genre, cast, and country
Export enriched datasets for downstream use

# Dataset-
Source: Netflix Movies and TV Shows dataset
File: netflix_titles.csv
Key Attributes:
Title, Type, Description
Cast, Country, Genre
Date Added, Duration

# Tech Stack & Libraries-
Python
Pandas, NumPy – Data handling
Matplotlib, Seaborn – Visualization
NLTK – Text preprocessing
Scikit-learn
-TF-IDF Vectorizer
-KMeans Clustering
-Cosine Similarity
-MultiLabelBinarizer
WordCloud – Text visualization

# Workflow Overview
1️⃣ Setup
1.Install required libraries
2.Configure plotting styles
3.Download NLTK stopwords
2️⃣ Data Loading
1.Load dataset using Pandas
2.Inspect structure and shape
3️⃣ Data Cleaning & Feature Engineering
1.Handle missing values
2.Normalize columns
3.Extract:
-Year added
-Runtime in minutes
-Genre lists
4.Create combined text features for NLP
4️⃣ Exploratory Data Analysis (EDA)
1.Content type distribution (Movies vs TV Shows)
2.Top genres on Netflix
3.Titles added per year
4.Runtime distribution
5.Top content-producing countries
5️⃣ Text Preprocessing
1.Lowercasing
2.URL and punctuation removal
3.Stopword filtering
4.Token length normalization
5.WordCloud visualization

# Machine Learning Components
TF-IDF + KMeans Clustering-
Vectorize cleaned text
Apply KMeans clustering (k = 8)
Interpret clusters via top keywords
Assign cluster labels to each title
Basic Content-Based Recommender-
Uses cosine similarity on TF-IDF vectors
Recommends titles based on description similarity
