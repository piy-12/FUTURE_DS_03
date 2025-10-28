📋 Project Overview

This project performs sentiment analysis on text data using the VADER Sentiment Analyzer in Python and visualizes the results in an interactive Power BI dashboard.

The dashboard provides actionable insights such as sentiment distribution, overall sentiment trend, and automated recommendations using Power BI’s KPI and Smart Narrative visuals.

⚙️ Technologies Used
Data Processing & Analysis

🐍 Python (Google Colab)

pandas – Data manipulation and cleaning

vaderSentiment – Sentiment analysis

openpyxl – Export cleaned data to Excel for Power BI

numpy – Numerical operations

Visualization & Reporting

📊 Microsoft Power BI Desktop

Dashboard creation and interactivity

KPI Visuals for tracking sentiment score vs. target

Smart Narrative for AI-generated recommendations

Conditional formatting and filters for intuitive analysis

🧩 Project Workflow
1. Data Collection

Text data (e.g., reviews, feedback, tweets) is collected and loaded into a pandas DataFrame in Google Colab.

2. Sentiment Analysis with VADER

Each text entry is analyzed using the VADER SentimentIntensityAnalyzer.

VADER returns 4 key metrics:

neg – Negative sentiment score

neu – Neutral sentiment score

pos – Positive sentiment score

compound – Overall polarity score (-1 to +1)

🚀 How to Run
1️⃣ Run Sentiment Analysis in Colab

Upload your dataset (.csv or .xlsx)

Run the notebook to generate vader_sentiments.xlsx

2️⃣ Import into Power BI

Open Power BI → Get Data → Excel

Select vader_sentiments.xlsx

Load and connect visuals

3️⃣ Customize & Publish

Modify visuals, KPI thresholds, and themes

Publish dashboard to Power BI Service (optional)
