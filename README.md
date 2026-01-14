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
Install required libraries
Configure plotting styles
Download NLTK stopwords
2️⃣ Data Loading
Load dataset using Pandas
Inspect structure and shape
3️⃣ Data Cleaning & Feature Engineering
Handle missing values
Normalize columns
Extract:
-Year added
-Runtime in minutes
-Genre lists
Create combined text features for NLP
4️⃣ Exploratory Data Analysis (EDA)
Content type distribution (Movies vs TV Shows)
Top genres on Netflix
Titles added per year
Runtime distribution
Top content-producing countries
5️⃣ Text Preprocessing
Lowercasing
URL and punctuation removal
Stopword filtering
Token length normalization
WordCloud visualization
