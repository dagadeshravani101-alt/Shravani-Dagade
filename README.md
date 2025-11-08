# Shravani-Dagade
This repository contains all five Data Science tasks I completed during my internship at Prodigy InfoTech. Each task demonstrates key data science concepts such as data preprocessing, visualization, machine learning, and model evaluation, implemented using Python and popular libraries like Pandas, NumPy, Matplotlib, and Scikit-learn.

Data Science & Machine Learning Portfolio

This repository serves as a portfolio showcasing my skills in Data Science, Machine Learning (ML), Exploratory Data Analysis (EDA), and Natural Language Processing (NLP), with a focus on applying these techniques to various real-world datasets.

The projects demonstrate proficiency in Python, common data science libraries, and the complete ML pipeline, from data cleaning and visualization to model building and evaluation.

#Technologies & Techniques

Category

Tools & Concepts

Languages

Python

Data Handling

Pandas, NumPy, Data Cleaning, Feature Engineering

Visualization

Matplotlib, Seaborn, Folium (Geospatial Mapping)

Machine Learning

Scikit-learn, Decision Tree Classification, Model Evaluation (Accuracy, Confusion Matrix)

NLP

TextBlob (Sentiment Analysis), WordCloud

Key Analysis

Exploratory Data Analysis (EDA), Correlation Analysis, Geospatial Visualization

# Project Structure & Overview

This repository contains five distinct analytical projects, each focusing on a different dataset and set of objectives:

Task 1: Healthcare Patient Data Analysis

Dataset: healthcare_dataset.csv

Focus: Core Exploratory Data Analysis (EDA) and data quality assessment.

Key Techniques: Initial data loading and inspection (df.head(), df.info()), calculating descriptive statistics (df.describe()), and checking for missing values (df.isna().sum()). The task provides a foundational demonstration of data preparation.

Task 2: Titanic Survival Prediction & Visualization

Dataset: train.csv (Kaggle Titanic dataset)

Focus: Analyzing key factors influencing survival outcomes.

Key Techniques: Comparative visualization using bar plots (sns.barplot) to show survival rates by categorical features (Gender, Passenger Class - PClass). Investigating relationships between continuous variables (Age vs. Fare) using scatter plots and quantifying relationships with a Correlation Heatmap.

Task 3: Bank Marketing Campaign Classification

Dataset: bank-additional.csv

Focus: Building a machine learning model to predict the success of a bank telemarketing campaign.

Key Techniques: Data preprocessing for ML (Label Encoding), splitting data into training and testing sets, implementing a Decision Tree Classifier (DecisionTreeClassifier with criterion='entropy'), and comprehensive model evaluation (Accuracy: ~90%, Confusion Matrix, and Classification Report).

Task 4: Twitter Sentiment Analysis

Dataset: twitter_validation.csv

Focus: Analyzing public sentiment toward various brands and topics from social media data.

Key Techniques: Text cleaning using regular expressions (re), calculating polarity and subjectivity using TextBlob, categorizing sentiment (Positive, Negative, Neutral), visualizing sentiment distribution, and generating Word Clouds to highlight key vocabulary.

Task 5: US Accidents Geospatial Mapping

Dataset: US_Accidents_March23.csv (Large-scale US accident data)

Focus: Geospatial analysis to identify accident hotspots across the US.

Key Techniques: Handling large datasets, utilizing the Folium library to create interactive maps, and implementing the HeatMap plugin to visually represent the density and location of high-severity accidents.

# Setup and Dependencies

To run the analysis notebooks locally, you'll need the following libraries installed:

# Recommended environment setup
pip install pandas numpy matplotlib seaborn scikit-learn textblob folium wordcloud

Ensure the required datasets are placed in the appropriate location as referenced in the scripts (or update the file paths).

Execute the Python scripts or Jupyter Notebooks for each task.
