<h2> Hello There <img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" height="25px"></h2>

<img align="right" src="https://github.com/rajput2107/rajput2107/blob/master/Assets/Developer.gif" width='200'/>

 
 
 
This is  Iris_Zero, and we are pleased to introduce our project on Forest Fire Detection and Prediction utilizing cutting-edge technologies such as Artificial Intelligence (AI), Machine Learning (ML), Deep Learning (DL), on Intel oneAPI server using Intel oneDAL and oneDNN.👨‍💻. 

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

### ✅ Conducted preliminary data analysis on numerical data and applied data augmentation techniques to images in order to better train and fit our model effectively

### ✅ Applied various model building alogorithms on numeric data like Logistic Regression, Random Forest, KNN, XGBoost Classifiers and trained and validate the Deep Neural Network model on imagery dataset for fire or no_fire image classification. Along with these we implemented Hyperparameter testing on numeric data

Accuracy of model on numeric dataset 
- [x] KNN --> 0.9315
- [x] Logistic Regression --> 0.91
- [x] RF --> 0.97
- [x] XGBoost --> 0.9726


Accuracy of model on Image dataset 
- [x] DNN ---> 0.54

Among all the models, we got XGBoost Classifier with highest accuracy, so we deployed the XGBoost Classifier model to create our Web Application and for image classfication the DNN produced an accuracy of 54%.

### ✅ The entire procedure is completed with the help of Intel oneDAL and AIToolkit and Intel oneDNN (TensorFlow) to get better results and faster computation(Intel oneAPI Data Analytics Library (oneDAL) and oneAPI Deep Neural Network Library (oneDNN))
![intel](https://user-images.githubusercontent.com/72274851/218504609-585bcebe-5101-4477-bdd2-3a1ba13a64a8.png)


## ⚡ Some Graphs involved in numeric dataset

- [x] XGBoost Classifier Confusion Matrix<br/>
![WhatsApp Image 2023-03-16 at 17 32 13](https://user-images.githubusercontent.com/62347601/225611081-dd889e13-466a-4cab-a1b1-fc46a3c90f92.jpg)
<br/>
- [x] Performed Data Preprocessing<br/>
![WhatsApp Image 2023-03-16 at 17 35 35](https://user-images.githubusercontent.com/62347601/225611682-bbe9e188-30c9-4cbf-bba4-3a05d47fbfda.jpg)
<br/>
- [x] Relationship between various features
![WhatsApp Image 2023-03-16 at 17 37 07](https://user-images.githubusercontent.com/62347601/225612214-992c753a-dfa2-4a1d-a0d9-682ab2b551c9.jpg)


## ⚡ Some Graphs involved in imagery dataset

- [x] Accuracy Achieved while training the model
![WhatsApp Image 2023-03-16 at 17 46 52](https://user-images.githubusercontent.com/62347601/225614650-bb77e6fb-53ad-421b-be0c-0d4bdafd6735.jpg)


- [x] Confusion matrix generated after passing test data to the trained model
![WhatsApp Image 2023-03-16 at 17 46 52](https://user-images.githubusercontent.com/62347601/225614723-4a7deca8-3670-410f-a8de-931b533e8af4.jpg)

- [x] loss value over the training data per epoch plot
![WhatsApp Image 2023-03-16 at 17 46 52](https://user-images.githubusercontent.com/62347601/225614788-ed4c2bdf-3457-4be3-8eb8-01614b3974b1.jpg)



## ⚡ Working of Web Application

https://user-images.githubusercontent.com/62347601/225616464-31cd97aa-a112-4af6-b389-7906fb9c9937.mp4



## ⚡ Working of Image Classifications
https://user-images.githubusercontent.com/62347601/225619458-1035442c-6759-4fac-86b7-f9f448b7fc3e.mp4



# What we learned ![image](https://user-images.githubusercontent.com/72274851/218499685-e8d445fc-e35e-4ab5-abc1-c32462592603.png)


![image](https://user-images.githubusercontent.com/72274851/220130227-3c48e87b-3e68-4f1c-b0e4-8e3ad9a4805a.png)

✅ The utilization of Intel oneAPI Data Analytics Library (oneDAL) can expedite big data analysis through the provision of highly optimized algorithmic building blocks for every phase of data analytics, encompassing preprocessing, transformation, analysis, modeling, validation, and decision-making, in batch, online, and distributed processing modes. This library enhances data ingestion and algorithmic computation to augment throughput and scalability. The uitilization of Intel oneAPI Deep Neural Network Library (oneDNN) has enabled heavy GPU and CPU intensive task like image processing etc.

✅ We have garnered knowledge in data preprocessing, cleaning, missing value handling, and categorical variable management. Exploratory data analysis may have been conducted to derive insights into variable relationships.

✅ We have acquired the ability to select pertinent machine learning algorithms for diverse problems, such as utilizing XGBClassfier for classification tasks and deep learning for image classification tasks and leanred about handling imagery data and performing data augmentation and classification.

✅ We have gained knowledge about multiple machine learning algorithms and their applicability in predicting forest fires using various textual, numerical and image data.

✅ We have gained experience in collecting and analyzing substantial amounts of data, including historical data, for training machine learning models.

✅ We have learned to compare model performance using appropriate statistical tests or visualizations to select the best model for the given problem.

Overall, predicting real-world phenomena using AI and Machine Learning is a demanding yet satisfying experience requiring a fusion of technical expertise.
