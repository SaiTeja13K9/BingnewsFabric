# Microsoft Fabric End-to-End Data Engineering Project: News Sentiment Analytics

# 📌 Overview

This project showcases an end-to-end data engineering pipeline leveraging Microsoft Fabric to process and analyze real-time news data sourced via the Bing News API. The goal is to ingest, transform, analyze sentiment, visualize insights, and automate alerts from live news content, demonstrating the robust capabilities of Microsoft's unified analytics platform.

# 🌟 Features & Highlights

- **Data Ingestion:** Fetch latest news using Bing News API.
- **Data Transformation:** Convert raw JSON to structured Delta tables using Spark notebooks.
- **Sentiment Analysis:** Perform real-time sentiment predictions (Positive, Negative, Neutral).
- **Visualization:** Generate insightful dashboards with Power BI.
- **Automated Alerts:** Leverage Microsoft Data Activator to set dynamic alerts based on sentiment.

# 🛠️ Technology Stack

- **Microsoft Fabric:** A unified analytics platform combining data engineering, data science, and BI tools.
- **Azure Data Factory:** Seamless data ingestion pipeline setup.
- **Synapse Data Engineering:** Spark-powered data transformation notebooks.
- **SynapseML:** Pre-built machine learning models for sentiment analysis.
- **Power BI:** Data visualization and dashboarding.
- **Microsoft Data Activator:** Real-time alerts for proactive data monitoring.

# 📊 Project Workflow

## 1. Data Ingestion
- Used Azure Data Factory within Microsoft Fabric to connect and fetch news data from Bing News API.

## 2. Data Transformation
- Employed Spark Notebooks (PySpark) to parse and transform raw JSON data into clean, structured Delta tables in Fabric Lakehouse.

## 3. Sentiment Analysis
- Applied SynapseML to classify news articles into sentiments (Positive, Neutral, Negative), enriching insights.

## 4. Visualization
- Created comprehensive dashboards in Power BI showcasing sentiment distributions, categories, and provider analytics.

## 5. Automated Alerts
- Configured Microsoft Data Activator to trigger alerts via email and Teams notifications based on critical negative news.

# 📑 File Structure


- data_pipeline
  - ingestion_pipeline.json
![image](https://github.com/user-attachments/assets/dbe29637-8428-4fa4-b57d-05e4835a768f)

- notebooks
  - transform_news_data_pipeline.ipynb
  - sentiment_analysis_with_synapseML.ipynb
- reports
  - news_sentiment_dashboard.pbix
- images
 ![image](https://github.com/user-attachments/assets/18ffe0e0-03bd-4fb4-867c-996e7827d190)
![image](https://github.com/user-attachments/assets/ab0f388f-9523-4a7c-8cb1-a5a3e7291565)



# 🚀 Quick Start

1. **Setup Azure Resources:** 
   - Create resource group, Bing News API, and Fabric workspace.

2. **Run Data Factory Pipeline:** 
   - Initiate pipeline to ingest latest news.

3. **Execute Transformation Notebooks:** 
   - Run PySpark notebooks to clean and structure data.

4. **Perform Sentiment Analysis:** 
   - Run SynapseML notebooks for sentiment predictions.

5. **Visualize in Power BI:** 
   - Open and refresh the dashboard to explore insights.

6. **Configure Alerts:** 
   - Set up alerts via Microsoft Data Activator.


# 🤝 Contributions

Contributions and improvements are warmly welcomed! Please submit issues or pull requests.

