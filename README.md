<h2> Hello There <img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" height="25px"></h2>

<img align="right" src="https://github.com/rajput2107/rajput2107/blob/master/Assets/Developer.gif" width='200'/>

 
This is  Iris_Zero, and we are pleased to introduce our project on Forest Fire Detection and Prediction utilizing cutting-edge technologies such as Artificial Intelligence (AI), Machine Learning (ML), Deep Learning (DL), and Intel ONEAPI.👨‍💻. 

## 👯 Project Overview

Our project aims to provide an efficient solution to the issue of forest fires by leveraging these advanced technologies to detect and predict forest fires in real time. With the help of AI and ML algorithms, we can accurately predict the possibility of a forest fire and provide early warning systems to minimize the damage caused.

We are confident that our project will benefit the environment and the community, and we look forward to presenting our findings and advancements in this field. 

## ⚡ Motivation Behind our Project
Forest fires wreaking havoc and destroying several irreplaceable ecosystems is common news in the past few years owing to climate change. The best solution to the issue is having a reliable detection system, which can pick up on the early signs of a forest fire and inform the authorities immediately for it’s speedy containment and also predict the air quality near the affected area. The lack of a reliable, automated system for detecting forest fires is the problem we are trying to solve here.

## ⚡ Outcome of our Project
The idea we are proposing will definitely help in preventing wildfires from reaching exorbitant levels. It can also in some cases help in preventing the forest-fire from breaking out at all and upholds the environmental concerns by predicting the air quality in affected areas. In the worst case scenarios we can have an early warning for a forest fire and the authorities can contain and put the fire out before it destroys a large area.

# How We built it ![image](https://user-images.githubusercontent.com/72274851/218502434-f6e66043-0db0-4f85-b7f4-f33b2d33df1f.png)

### ✅ Initially, we gathered a numeric dataset pertaining to Algerian Forest Fire with the intention of predicting the likelihood of such incidents. Additionally, we acquired a Flame Dataset containing aerial imagery of pile burns to supplement our analysis.

### ✅ We conducted frame-wise classification to identify instances of forest fires within frames. Additionally, we applied feature extraction techniques to our numeric data and implemented data pre-processing methods.

### ✅ Conducted preliminary data analysis on numerical data and applied data augmentation techniques to images in order to train our model effectively

### ✅ Applied various model building alogorithms on numeric data like Logistic Regression, Random Forest, KNN, XGBoost Classifiers and trained and validate the Deep Neural Network model on imagery dataset. Along with these we implemented Hyperparameter testing on numeric data

Accuracy of model on numeric dataset 
- [x] KNN --> 0.9315
- [x] Logistic Regression --> 0.91
- [x] RF --> 0.97
- [x] XGBoost --> 0.9726

Among all the models, we got XGBoost Classifier with highest accuracy, so we deployed the XGBoost Classifier model to create our Web Application.

### ✅ The entire procedure is completed with the help of Intel oneDAL and AIToolkit and TensorFlow to get better results and faster computation(Intel oneAPI Data Analytics Library (oneDAL))
![intel](https://user-images.githubusercontent.com/72274851/218504609-585bcebe-5101-4477-bdd2-3a1ba13a64a8.png)


## ⚡ Some Graphs involved in numeric dataset

- [x] XGBoost Classifier Confusion Matrix
![WhatsApp Image 2023-03-16 at 17 32 13](https://user-images.githubusercontent.com/62347601/225611081-dd889e13-466a-4cab-a1b1-fc46a3c90f92.jpg)

![WhatsApp Image 2023-03-16 at 17 35 35](https://user-images.githubusercontent.com/62347601/225611682-bbe9e188-30c9-4cbf-bba4-3a05d47fbfda.jpg)
- [x] Performed Data Preprocessing

![WhatsApp Image 2023-03-16 at 17 37 07](https://user-images.githubusercontent.com/62347601/225612214-992c753a-dfa2-4a1d-a0d9-682ab2b551c9.jpg)
- [x] Relationship between various features


## ⚡ Some Graphs involved in imagery dataset
