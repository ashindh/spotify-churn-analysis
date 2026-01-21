# 🎵 Spotify User Churn Analysis & Dashboard

![Dashboard Preview](Screenshot 2026-01-19 211450.png)

## 📊 Project Overview
This project focuses on analyzing user churn patterns within a Spotify dataset. The goal was to identify key factors contributing to user attrition (churn) and to visualize user engagement behaviors across different demographics, subscription plans, and devices.

Using **Power BI**, I created an interactive dashboard that helps stakeholders understand retention trends and make data-driven decisions to improve customer loyalty.

## 📂 Dataset
The analysis is based on the `spotify_churn_dataset.csv`, which contains user-level data including:
* **Demographics:** Age, Gender, Country.
* **Subscription Details:** Plan Type (Free, Premium, Family, Student), Payment info.
* **Engagement Metrics:** Listening Time, Songs per Day, Skip Rate, Offline Listening.
* **Ad Exposure:** Ads listened to per week.
* **Churn Status:** Whether the user has left the platform (`1` = Churned, `0` = Retained).

## 💡 Key Insights & Features
Based on the analysis visualized in the Power BI report:

### 1. Global Churn Overview
* **Overall Churn Rate:** Visualized the global churn percentage (approx. 25.89%) against the retained user base.
* **Geographic Split:** Broken down user retention by country to identify high-risk regions.

### 2. Subscription & Revenue Analysis
* **Risk by Plan:** Compared churn rates across different tiers (Free vs. Premium vs. Family).
* **Findings:** "Free" tier users showed different churn behaviors compared to "Family" or "Student" plan subscribers, highlighting the effectiveness of premium lock-in.

### 3. User Behavior Patterns
* **Ad Tolerance:** Analyzed how the frequency of ads (Ads/Week) correlates with a user's decision to leave.
* **Device Usage:** Segmented churn data by device (Mobile, Web, Desktop) to see if specific platforms drive higher attrition.

## 🛠️ Tech Stack
* **Data Visualization:** Microsoft Power BI (DAX, Power Query)
* **Data Processing:** Excel / CSV
* **Data Source:** `spotify_churn_dataset.csv`

## 📸 Dashboard Screenshots

### User Engagement & Ad Analysis
![Engagement Metrics](Screenshot 2026-01-19 211537.png)

### Audience Demographics
![Subscription Analysis](Screenshot 2026-01-19 211603.png)

## 🚀 How to Run
1.  Clone this repository.
2.  Open the `Spotify.pbix` file using **Microsoft Power BI Desktop**.
3.  The data source is linked relative to the file; if it fails to load, go to `Transform Data` > `Data Source Settings` and point it to the local `spotify_churn_dataset.csv` file.

## 🔮 Future Scope
* **Predictive Modeling:** Implementing Machine Learning models (Logistic Regression/Random Forest) to predict churn probability for individual users.
* **Sentiment Analysis:** If review data becomes available, integrating text analysis to understand the "why" behind the churn.

## 📌 Conclusion
The analysis reveals that user retention on Spotify is heavily influenced by subscription models and ad tolerance. With an overall churn rate of **~25.89%**, the data suggests that:
* **The "Freemium" Friction:** Users on the **Free** plan exhibit significantly different behavioral patterns compared to Premium/Family subscribers, indicating that ad interruptions are a primary driver of churn.
* **Engagement vs. Retention:** High "Skip Rates" and lower "Listening Times" are early warning signs of potential churn. Users who are deeply engaged (high listening hours, low skips) are far less likely to cancel.
* **Platform Stickiness:** The **Family** and **Student** plans show higher retention rates, likely due to the shared value and lower price barriers, suggesting that bundling services is an effective retention strategy.

## 🧠 Key Learnings
Through this project, I gained practical experience in:
* **End-to-End Analysis:** Transforming raw CSV data into actionable insights using Power BI.
* **Data Modeling:** Creating relationships between demographic data and behavioral metrics to segment users effectively.
* **Visual Storytelling:** Designing an interactive dashboard that allows stakeholders to filter by country, device, and subscription type to pinpoint problem areas.
* **Strategic Thinking:** Moving beyond simple "counts" to calculate meaningful KPIs like **Churn Rate %** and correlation between **Ad Frequency** and user drop-off.
---
**Author:** Ashindh Anil
*Aspiring Business Analyst & Data Enthusiast*
