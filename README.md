# Coursera-IBM-Applied-Data-Science-Capstone
This project aims to predict the success of SpaceX's Falcon 9 first-stage landings to estimate launch costs. By leveraging data science techniques, we analyze historical launch data to determine which factors contribute most to a successful booster recovery.



## Project Overview
SpaceX has revolutionized space travel by making rockets reusable. This project covers the entire data science pipeline:

Data Collection: Retrieving data via SpaceX API and Web Scraping (Wikipedia).

Exploratory Data Analysis (EDA): Insights gained through SQL and Pandas.

Data Visualization: Interactive maps with Folium and statistical plots with Matplotlib/Seaborn.

Interactive Dashboard: A dynamic web app built with Plotly Dash.

Predictive Modeling: Comparing Classification models (SVM, KNN, Trees) to find the best predictor.

## Tech Stack
Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Folium, Plotly Dash, Matplotlib, Seaborn

Environment: Jupyter Lab, GitHub

## Results
Launch Site Influence: Proximity to coastlines and specific launch pads significantly impacts landing success rates.

Payload Correlation: Heavier payloads show different success patterns depending on the target orbit.

Best Performing Model: While all models (SVM, KNN, Decision Tree, Logistic Regression) achieved a similar test accuracy of 83.33%, the Decision Tree was considered the best performer based on its training stage efficiency and hyperparameter tuning result
