📊 Twitter Entity Sentiment Analysis
This project analyzes and visualizes public sentiment from tweets related to various brands and topics. The goal is to understand how people feel (Positive, Negative, Neutral, Irrelevant) about specific entities using basic data analysis and visualization techniques.

📁 Dataset
Source: Kaggle - Twitter Entity Sentiment Analysis

Files Used: twitter_training.csv

🔍 Project Tasks
1. Data Loading & Cleaning
Loaded and explored the dataset (id, entity, sentiment, text)

Dropped 686 rows with missing text values

2. Sentiment Counts
Counted sentiment types: Positive, Negative, Neutral, Irrelevant

Visualized using bar chart and pie chart

3. Entity-wise Sentiment Distribution
Identified top 10 most-mentioned entities

Analyzed how sentiment varies per brand

Created stacked bar chart for sentiment distribution

4. Text Cleaning
Removed URLs, mentions, hashtags, numbers, punctuation

Applied lowercasing and whitespace trimming

5. Positive Tweets
Filtered and visualized top entities with irrelevant tweets to identify noisy data

6. Additional EDA
Number of tweets per brand

Bar charts with value labels


📈 Key Insights
Most Frequent Entities: Brands like Amazon, Google, and Apple appeared most in the dataset.

Dominant Sentiment: Neutral tweets dominated overall sentiment, followed by Negative and Positive.

Entity Sentiment Variation: Some brands had more negative sentiment (e.g., Uber), while others like Apple had a more balanced or positive view.

Irrelevant Tweets: Irrelevant data was significant (~12.8K tweets); these can be excluded for cleaner sentiment modeling.

⚙️ Tools Used
Python (Pandas, Matplotlib, Seaborn)

Regular Expressions (re)

Jupyter/Colab

GitHub

