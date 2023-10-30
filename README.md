# Project 4 - Fire_detection

![fire images detection](https://github.com/Karanmanolaa/Fire_detection/assets/144649975/5c609984-3c1e-4ddb-a03f-596b38a26bf5)


# Table of Content
- Overview
- Problem Statement and Motivation
- Technical Aspects
- Challenges and Solutions
- Visualizations


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

  
![download](https://github.com/Karanmanolaa/Fire_detection/assets/144649975/14cf2435-5f65-4fa4-aefb-2042ed2e6644)

![download (1)](https://github.com/Karanmanolaa/Fire_detection/assets/144649975/d6aa6e83-8659-4e21-9093-d2facf8083fd)


![download (2)](https://github.com/Karanmanolaa/Fire_detection/assets/144649975/363d43f9-18a6-44b1-b63d-b8dc53a6f013)


![download (3)](https://github.com/Karanmanolaa/Fire_detection/assets/144649975/21d0e930-914b-40fc-a872-f98da0bf7dbd)


![download (4)](https://github.com/Karanmanolaa/Fire_detection/assets/144649975/150fe914-6dfc-44af-921f-960b034194a7)

# Below is of CNN
![download (5)](https://github.com/Karanmanolaa/Fire_detection/assets/144649975/f8a6108f-72bb-4f8b-8cba-50ef0b5f1dc1)



# Below is of resnet50

![download (6)](https://github.com/Karanmanolaa/Fire_detection/assets/144649975/8f783c2c-eda2-427f-9e74-567f7f5e8a51)





