# Predicting National Team Selection in Soccer (2021-2022 Season)

This project aims to predict whether a professional soccer player will be selected for their national team based on club-level performance metrics using logistic regression.

## 📊 Project Overview

- **Goal:** Use data science and machine learning to model national team selection using real player stats.
- **Dataset:** Player statistics from the top five European leagues (Premier League, La Liga, Serie A, Bundesliga, Ligue 1) for the 2023–2024 season.
- **Target Variable:** `Selected` (1 = selected for national team, 0 = not selected). This was generated based on goals scored and minutes played.

## 🛠️ Tools Used

- Python  
- Jupyter Notebook  
- Pandas, Seaborn, Matplotlib  
- Scikit-learn (for logistic regression model)

## 📁 Files Included

- `soccer_selection_analysis.ipynb` – the full analysis and model notebook  
- `top5-players.csv` – the dataset used in this project  
- `requirements.txt` – list of required packages  
- `soccer_project_report.pdf` – final report (explaining the why, what, and how)  
- `README.md` – project overview

## 📌 Results

- **Model Used:** Logistic Regression  
- **Accuracy:** 99.5%  
- Strong predictors of national team selection were: **Goals scored** and **Minutes played**  
- Visuals include:
  - Scatter plot: Goals vs Minutes Played
  - Pair plot of key features colored by selection

## 📚 Citations

- Aktas, O. (2024). *All Football Players Stats in Top 5 Leagues 23/24*. Kaggle.  
  https://www.kaggle.com/datasets/orkunaktas/all-football-players-stats-in-top-5-leagues-2324
- AI assistance from OpenAI's ChatGPT was used for brainstorming, markdown structuring, and editing support.

## 🔄 Future Work

- Use real national team call-up lists for accurate labeling  
- Compare logistic regression with more advanced models  
- Include team rankings or player positions as additional features
