# 📊 Social Media Engagement Analysis | SQL + Power BI

## 📌 Project Overview
This project analyzes social media engagement and sentiment data to identify key drivers of user interaction and content performance. It explores how sentiment and toxicity influence engagement, helping improve content strategy, platform growth, and user experience.

---

## 🎯 Objectives
- Analyze overall engagement across platforms and content types  
- Identify top-performing platforms based on engagement metrics  
- Evaluate content categories driving the highest interaction  
- Understand the impact of sentiment and emotional tone on engagement  
- Examine how toxicity affects user interaction  
- Analyze time-based engagement trends and growth patterns  

---

## 🧠 Business Problem
Social media platforms aim to maximize meaningful engagement while maintaining healthy community interactions.

Understanding:
- What type of content performs best  
- Which platforms drive engagement  
- How sentiment and toxicity impact performance  

...is essential for improving user retention, platform growth, and trust & safety strategies.

---

## 🗂️ Dataset
- **Source:** https://www.kaggle.com/datasets/subashmaster0411/social-media-engagement-dataset  
- **Type:** Synthetic post-level data  

### Features:
- Platform, topic category, location, language  
- Likes, shares, comments, impressions  
- Engagement rate  
- Sentiment & emotion indicators  
- Toxicity scores  
- Brand & campaign data  

---

## 🏗️ Data Modeling & SQL Design
The dataset was transformed from a flat structure into a normalized relational schema.

### Tables:
- `posts` → core metadata  
- `engagement` → interaction metrics  
- `sentiment` → sentiment & toxicity  
- `campaigns` → campaign/brand data  

📄 Schema: `sql/schema_and_setup.sql`

---

## 🔍 Key Business Questions
- Which platforms drive the highest engagement?  
- Which content categories perform best?  
- How does sentiment affect engagement rates?  
- Does toxicity reduce engagement?  
- How has engagement changed over time?  
- Which time periods show peak engagement?  
- Do high impressions convert into engagement?  

---

## ⚙️ Analysis Approach

### Data Preparation
- Data cleaning and validation  
- Data type standardization  

### SQL Analysis
- Multi-table JOINs  
- Aggregations and KPI calculations  
- CASE statements for segmentation  

📄 Queries:
- `sql/02_kpi_analysis.sql`  
- `sql/03_time_and_growth_analysis.sql`  

### Time-Based Analysis
- Trend and growth analysis  

### Visualization (Planned)
- Power BI dashboards  

---

## 📈 Key Insights
- Some platforms consistently outperform others in engagement  
- Certain content categories drive higher interaction  
- Positive sentiment correlates with higher engagement  
- Higher toxicity tends to reduce engagement  
- Engagement varies across time periods  
- High impressions do not always convert into engagement  

---

## 🛠️ Tools & Technologies
- MySQL  
- SQL (JOINs, aggregations, CASE statements)  
- Power BI  

---

## 📁 Repository Structure
