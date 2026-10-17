# YouTube Trending Video Analytics 📊

## 📌 Project Overview

The **YouTube Trending Video Analytics** project analyzes trending YouTube videos from India, the United States, and Great Britain. The project explores video popularity, category performance, viewer engagement, title sentiment, and trending patterns using data analysis and visualization techniques.

An interactive dashboard was created using Tableau Public to present key insights in an easy-to-understand visual format.

## 🎯 Objectives

- Analyze views, likes, dislikes, and comments on trending videos.
- Identify popular YouTube video categories.
- Compare video performance across different regions.
- Perform sentiment analysis on video titles and tags.
- Explore trending patterns over time.
- Create visualizations and an interactive Tableau dashboard.

## 🛠️ Tools and Technologies

- **Python** — Data cleaning, analysis, and sentiment analysis
- **Pandas and NumPy** — Data manipulation and preprocessing
- **Matplotlib and Seaborn** — Data visualization
- **TextBlob** — Sentiment analysis
- **SQL and SQLite** — Data storage and querying
- **Tableau Public** — Interactive dashboard creation
- **Google Colab** — Cloud-based Python development

## 📂 Dataset

The project uses the YouTube Trending Video Statistics dataset, which contains information about trending videos from multiple countries.

Dataset source: [YouTube Trending Video Dataset — Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new)

The dataset includes information such as:

- Video title and video ID
- Category ID
- Trending date
- Publication time
- Views, likes, and dislikes
- Comment count
- Tags and descriptions

## 🔍 Project Workflow

### 1. Data Collection
Collected YouTube trending video data for India, the United States, and Great Britain.

### 2. Data Cleaning
- Combined data from multiple regions.
- Handled missing values.
- Converted dates and numerical columns into appropriate formats.
- Removed duplicate records and invalid engagement values.

### 3. Exploratory Data Analysis (EDA)
Analyzed video views, engagement metrics, category performance, and regional differences.

### 4. Sentiment Analysis
Used TextBlob to estimate sentiment polarity from video titles and tags.

### 5. SQL Analysis
Used SQLite queries to analyze category rankings and regional performance.

### 6. Data Visualization
Created charts to explore category popularity, sentiment, regional comparisons, and trending patterns.

### 7. Tableau Dashboard
Built a Tableau dashboard containing:
- Top Videos by Views
- Category Performance
- Regional Comparison

## 📈 Key Deliverables

- Cleaned YouTube dataset
- Exploratory data analysis charts
- Sentiment analysis results
- SQL analysis outputs
- PDF project report
- Interactive Tableau dashboard

## 📊 Tableau Dashboard

Explore the interactive dashboard:

[**YouTube Trending Video Analytics — Tableau Public**](https://public.tableau.com/authoring/YouTubeTrendingVideoAnalytics_17922336276350/YouTubeTrendingVideoAnalyticsDashboard#1)

*Note: Replace this authoring link with your public viewer link if necessary.*

## 📁 Repository Structure

```text
youtube-trending-video-analytics/
│
├── README.md
├── cleaned_youtube_data.csv
├── youtube_sentiment_results.csv
├── YouTube_Trending_Analytics_Report.pdf
│
├── top_categories.png
├── region_comparison.png
├── sentiment_vs_views.png
└── trending_over_time.png
```

*The repository structure may vary depending on which project files are uploaded.*

## 💡 Learning Outcomes

Through this project, I gained practical experience in:

- Data cleaning and preprocessing
- Exploratory data analysis
- Python-based data visualization
- Sentiment analysis using NLP techniques
- SQL querying and database management
- Interactive dashboard development using Tableau
- Presenting analytical findings through reports and visualizations
- 
##🚀 Conclusion

This project demonstrates an end-to-end data analytics workflow, from data preparation and analysis to visualization and dashboard development. It helped develop practical skills in Python, SQL, sentiment analysis, and business intelligence.

Project Category: Data Analytics | Data Visualization | Natural Language Processing

Tools: Python, Pandas, TextBlob, SQLite, Tableau Public
