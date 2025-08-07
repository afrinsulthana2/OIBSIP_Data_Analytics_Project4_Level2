Unveiling the Android App Market: Analyzing Google Play Store Data
Project Overview
This project focuses on analyzing data from the Google Play Store to uncover key insights about app performance, user behavior, and market dynamics. It involves data cleaning, categorization, statistical analysis, sentiment evaluation, and visual representation to understand trends within the Android app ecosystem.

Dataset
Dataset Source: https://www.kaggle.com/datasets/utshabkumarghosh/android-app-market-on-google-play

The dataset includes features such as App Name, Category, Rating, Reviews, Size, Installs, Price, Content Rating, Genres, and User Reviews.

Objectives
Clean and preprocess the dataset for accurate analysis.

Explore category-wise distribution and trends in app metrics.

Analyze user reviews to extract sentiment-based insights.

Create meaningful visualizations to interpret findings effectively.

Key Tasks
1. Data Cleaning and Preparation
Handle missing and inconsistent data.

Convert data types for correct analysis.

Normalize price, installs, and size columns.

2. Category and Metrics Analysis
Examine the distribution of apps across different categories.

Identify top-rated and most downloaded categories.

Analyze trends in ratings, reviews, app size, and price.

3. Sentiment Analysis
Perform sentiment analysis on user reviews using NLP techniques.

Classify reviews into positive, negative, and neutral sentiments.

4. Visualization
Use visual tools to present data trends clearly.

Implement bar charts, histograms, pie charts, scatter plots, and heatmaps.

Tools and Technologies Used
Python

Pandas – Data manipulation

NumPy – Numerical computations

Matplotlib, Seaborn – Static visualizations

Plotly – Interactive visualizations

TextBlob or NLTK – Sentiment analysis

Jupyter Notebook – Development environment

Outcomes
A complete understanding of how apps are distributed across various categories.

Insights on what makes apps successful based on installs, reviews, and ratings.

Sentiment-based classification of user feedback for app improvement strategies.

Visual summaries to support strategic decision-making for app developers and marketers.

Learning Objectives
Improve data wrangling and cleaning skills using Python.

Gain experience in statistical and sentiment analysis.

Develop clear and concise visual representations of complex data.

Apply concepts from data visualization and natural language processing in real scenarios.

How to Run
Install Dependencies
Run the following command to install all required packages:

bash
Copy
Edit
pip install -r requirements.txt
Start the Streamlit App
Navigate to the project folder and run:

bash
Copy
Edit
streamlit run app.py
Open in Browser
After running the command, a browser window will automatically open (usually at http://localhost:8501/) displaying the dashboard.
