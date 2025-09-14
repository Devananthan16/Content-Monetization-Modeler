# Content-Monetization-Modeler
Predict YouTube ad revenue using machine learning on large-scale video performance data.

This project builds an end-to-end regression pipeline to estimate ad revenue from video metrics and deploys a simple Streamlit app for real-time predictions.

Project Overview

-Domain: Social Media Analytics

-Dataset Size: 122,000+ video records

-Target Variable: ad_revenue_usd


Key Features

-Performed data cleaning (handled 5% missing values and removed 2% duplicates)

-Conducted EDA to explore relationships and detect outliers

 -Engineered new features:

 -engagement_rate = (likes+comments)/views

 -watch_ratio = watch_time/(views * video_length)


-Built and compared 3 regression models:

   -Linear, Ridge, Lasso

-Achieved R² ≈ 0.94 with low RMSE and MAE

-Deployed a Streamlit web app for real-time predictions


Tech Stack

-Python, Pandas, NumPy, Scikit-learn, Matplotlib

-Streamlit, Joblib

-Jupyter Notebook

-Git / GitHub

