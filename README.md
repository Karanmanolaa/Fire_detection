# Project 4 - Fire_detection

# Table of Content
- Overview
- Problem Statement and Motivation
- Technical Aspects
- Visualizations
- Challenges and Solutions

# 1- Overview :
The Fire Detection project focuses on building a deep learning model that can automatically detect fires in images. The dataset includes 755 fire and 
244 non_fire images. The dataset was sourced from Kaggle.

# 2- Problem Statement and Motivation :

The primary aim is to enable real-time fire detection for applications in fire prevention, early warning systems, and safety and security contexts.
I am doing this project because there are more fires happening lately, and it's important to catch them early. Current methods aren't always great, like humans watching for fires, which can make mistakes. I have trained the model that's good at finding fires on its own. This will help keep people safe and prevent big fires from getting worse.

# 3- Technical Aspects :
In this project i have used python programming language and its libraries - scikit-learn,pandas,numpy,tensorflow,keras,os,
for different purpose like
- Performed Explolatory data analysis using matplotlib and seaborn.
- Created new feature (feature engineering) age bins.
- I tried several models like Linear regression,decision trees.
- Used hyperparameter tuning and got the best model RandomForestRegressor with r2 score of 0.8080 and
-  MSE: 7386012.305294765
-  MAE: 1069.7527665859436

# 4 - Challenges and Solutions:
- Challenges: Limit data
- Solutions : Utilized models like Random Forest (with tuned hyperparameters) that are robust and less prone to overfitting, making the model more reliable when dealing with limited data.

# 5 - Visualizations:

  
