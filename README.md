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
In this project i have used python programming language and its libraries - scikit-learn,pandas,numpy,tensorflow,keras,os for different purpose like
- Labeled fire images as 1 and non fire as 0
- created visual representations of sample fire and non-fire images to get a better idea of what the computer was learning.
- Used data augmentation for handling class imbalance between the images of fire and non fire.
- I trained two different models. First, I built a custom model using Convolutional Neural Networks (CNN), which achieved an accuracy of 0.98. Second, I used a pre-trained ResNet50 model, which achieved an accuracy of 0.97.

# 4 - Challenges and Solutions:
- Challenges: Data imbalanced(less images of non fire then fire)
- Solutions : To address this data imbalance issue, data augmentation techniques were employed. Data augmentation involves creating additional training examples by applying various transformations (such as rotation, scaling, and flipping) to the existing data. This helped balance the dataset, improving the model's ability to learn and make accurate predictions for both fire and non-fire scenarios.

# 5 - Visualizations:

  
