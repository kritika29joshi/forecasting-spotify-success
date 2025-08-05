# Hit Predictor: Forecasting Song Success with Machine Learning
This project aims to predict whether a song is likely to become a hit using machine learning models trained on the Spotify dataset.

## Project Overview
Millions of songs are released each year, but only a small percentage go viral. This project uses Python-based ML techniques to identify the audio features that influence a song's popularity and forecasts "hits" based on historical trends.

- **Dataset:** Spotify tracks with 20+ audio and metadata features (~41,000 rows)
- **Goal:** Predict whether a song is a "hit" (defined as top 25% in popularity)
- **Approach:** Supervised classification using Logistic Regression, Random Forest, and SVM
- **Best Model:** Random Forest — 79.5% accuracy and 84% hit recall

## Tools & Libraries

- Python, Pandas, NumPy
- Scikit-learn (Logistic Regression, Random Forest, SVM)
- Matplotlib & Seaborn for data visualization
- Pipelines, Imputation, Standard Scaling
- Stratified train-test splits to maintain class balance

## Key Takeaways

- Class imbalance and feature scaling significantly impacted model performance
- Pipelines helped prevent data leakage and ensured robust workflows
- Random Forest proved most effective for hit detection, showing potential for real-world music industry use cases

## Files in This Repo

- `ai_ml_project_code.ipynb` – Full code with preprocessing, training, and evaluation
- `AI_ML_Project_Report.pdf` – Detailed project write-up with findings and challenges

## Report Access

If you're viewing this for hiring purposes, feel free to view both:
- [Full Report (PDF)](./AI_ML_Project_Report.pdf)
- [Jupyter Notebook](./ai_ml_project_code.ipynb)

## Created by
**Kritika Joshi**  
Business Analytics & AI, University of Texas at Dallas  
[LinkedIn](https://www.linkedin.com/in/kj-kritikajoshi/)
