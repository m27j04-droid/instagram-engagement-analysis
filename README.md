# instagram-engagement-analysis
A Power BI dashboard to analyze social media engagement metrics such as likes, comments, shares, impressions, and engagement rate to understand content performance and audience behavior.
Got it — here is your **clean GitHub README.md in the same style as your previous project (simple, structured, professional, and student-friendly)** 👇

---
📊 Social Media Engagement Dashboard (MS Excel & Power BI)

---
🧾 Project Overview

This project is a **Social Media Engagement Dashboard** built using **Microsoft Power BI**. It analyzes social media performance data to track user engagement and content effectiveness across platforms like Instagram and YouTube.

The dashboard helps in understanding how audiences interact with content using metrics such as likes, comments, shares, impressions, and engagement rate.

---
🎯 Objectives

* To track and analyze social media engagement metrics
* To study likes, comments, shares, and impressions
* To identify best-performing content
* To analyze engagement trends over time
* To determine effective posting times
* To suggest content strategy improvements

---

🛠️ Tools & Technologies Used

* Microsoft Excel (Data Cleaning & Preparation)
* Microsoft Power BI (Data Visualization & Dashboard Creation)
* DAX (Data Analysis Expressions)

---

📂 Dataset Description

The dataset includes the following fields:

* Post ID
* Post Type (Reel, Image, Video, Carousel)
* Date & Time of Posting
* Likes
* Comments
* Shares
* Impressions
* Engagement Rate
* Category

---
⚙️ Methodology

1. Data collection from social media sources or datasets
2. Data cleaning in Excel
3. Importing data into Power BI
4. Creating calculated measures using DAX
5. Building KPIs and visuals
6. Adding slicers for interactivity
7. Analyzing engagement patterns
8. Generating insights and conclusions

---

📊 Dashboard Features

* 📌 KPI Cards (Total Likes, Comments, Engagement Rate, Total Posts)
* 📊 Bar Chart (Top Performing Posts)
* 📈 Line Chart (Engagement Trend Over Time)
* 📉 Column Chart (Post Type Analysis)
* 🎛️ Slicers (Date, Post Type, Category)

---

🧮 DAX Formulas Used

```DAX id="avg1"
Avg Engagement Rate = AVERAGE(Sheet1[engagement_rate])
---

```DAX id="month1"
Month = FORMAT(Sheet1[Date], "MMM YYYY")
---

🔍 Key Insights

* Reels and video content show higher engagement compared to images
* Engagement varies across different time periods
* A small number of posts generate majority of interactions
* Post type strongly affects engagement rate
* Consistent posting improves audience reach

---

⏰ Best Posting Time Analysis

* Evening hours generally show higher engagement
* Weekends perform better than weekdays
* Posting consistently improves visibility

---
💡 Recommendations

* Focus more on Reels and short videos
* Post during peak engagement hours
* Use trending hashtags and relevant topics
* Maintain a consistent posting schedule
* Analyze past performance before creating new content

🚀 How to Run This Project

1. Clone the repository
2. Open the Power BI file (.pbix)
3. Load the dataset
4. Refresh data if needed
5. Explore dashboard using slicers
------
📁 Project Structure
Social-Media-Engagement-Dashboard/
│
├── data/
│   └── social_media_data.xlsx
│
├── dashboard/
│   └── engagement_dashboard.pbix
│
├── images/
│   └── dashboard.png
│
└── README.md

👩‍💻 Author

Muskan
M.A. Economics Student (sem.2)| Aspiring Data Analyst
