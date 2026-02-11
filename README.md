# Projet-3: Video Game Sales Prediction with Linear Regression 📊

<p align="center">
<img width="1200" height="400" alt="Banner Data" src="https://github.com/user-attachments/assets/326fb701-be5d-48fc-b3c3-dd8995eeae27" />
</p>

## 📌 Project Overview

Can we predict the **global sales of a video game** based on its product features and player engagement metrics?
This project combines two Kaggle datasets:
- Steam game data (price, playtime, reviews, scores…)
- Global video game sales data

The objective is to build a supervised machine learning model capable of estimating Global_Sales using measurable indicators available at or shortly after release.

## 🎯 Objectives
Merge Steam and global sales datasets
**Identify key variables** influencing commercial performance
Build a **predictive model (Linear Regression)**
Evaluate performance using **MSE & R²**
Extract **actionable business insights**

## 📊 Dataset & Features
**🎯 Target Variable**
`Global_Sales`

**📌 Explanatory Variables**
`Price`
`Required_Age`
`Achievements`
`Average_Playtime`
`Median_Playtime`
`User_Score`
`Critic_Score`
`Positive_Reviews`
`Negative_Reviews`

These variables capture both:

- 🎮 Product attributes
- ⭐ Quality perception
- ⏱️ Player engagement
- 🔍 Exploratory Data Analysis (EDA)

## 📈 TL;DR
**🔎 Quick Exploration (EDA)**

**- Strongest correlation with Global Sales:**
`Positive_Reviews` and `Critic_Score` show the most significant positive relationship with commercial performance.

**- Engagement is more predictive than price:**
`Average_Playtime` demonstrates a meaningful link with sales, suggesting that retention depth reflects economic value.

**- Price impact remains limited:**
`Price` alone does not strongly explain performance. High-priced games do not systematically outperform lower-priced titles.

**- Review volume acts as a visibility multiplier:**
The total number of reviews (`positive` + `negative`) is strongly associated with sales, indicating an exposure dynamic beyond pure sentiment.

**📊 Business Interpretation**

**- Scores vs Sales:**
Higher `User_Score` and `Critic_Score` tend to align with stronger commercial performance, but quality perception alone is insufficient.

**- Engagement depth matters:**
Titles with longer median and average playtime generally generate stronger global revenue.

**- Exposure dynamics:**
Review volume likely amplifies algorithmic visibility, reinforcing a feedback loop between player engagement and sales.

**- Structural limitation:**
The model captures measurable engagement and perception signals, but does not integrate: Marketing intensity, Franchise power, Platform exclusivity, Release timing

## 🤖 Model
**Model type:** Linear Regression (Scikit-Learn)
**Train/Test split**
**Performance metrics:** MSE (Mean Squared Error) / R² Score

The model explains a significant portion of variance in `Global_Sales`, while highlighting the limits of structured quantitative data in entertainment industries.

## 💡 Business Insights

- Engagement metrics are strong commercial indicators.
- Volume of reviews acts as a visibility amplifier.
- Quality perception influences sales, but is not sufficient alone.
- Predictive models should combine behavioral + contextual features.

**👉 Commercial success is a mix of engagement + perception + exposure.**

## 📈 Visualizations
<img width="773" height="479" alt="image" src="https://github.com/user-attachments/assets/f039def7-0ca6-494b-8d11-8bd39d14df48" />

<img width="778" height="479" alt="image" src="https://github.com/user-attachments/assets/7fd29907-0cb5-4dcc-a2e5-3a8fee1bf479" />

<img width="778" height="479" alt="image" src="https://github.com/user-attachments/assets/d2f75d9f-0301-49d3-89e2-988e63aa771c" />

<img width="778" height="479" alt="image" src="https://github.com/user-attachments/assets/e7a22760-2652-474f-9f18-54000d7791fa" />

## 🚀 Deliverables

- 📓 Full [Jupyter Notebook](https://github.com/KeweSambe/Modele-Prediction-Popularit-Steam/blob/main/Mod%C3%A8le%20pr%C3%A9dictif%20linear%20regrssion%20K%C3%A9w%C3%A9%20SAMBE.ipynb)
- 📊 Data visualizations
- 🤖 Predictive model
- 📝 Executive summary (this README)

## 📂 Data Source
All data used comes from **[Kaggle](https://www.kaggle.com/)** :

👉 [Link to the dataset "Steam's daily sales"](https://www.kaggle.com/datasets/hdcortes/daily-steam-sales)

<sub>*All rights belong to their respective authors.*</sub>
