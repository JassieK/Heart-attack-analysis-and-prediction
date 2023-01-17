# Heart-attack-analysis-and-prediction
## Introduction
I have trained a model which will predict whether a person is prone to heart attack based on his physical condition. I Scaled the training data and classified it. Fed the test Data into the system and predict the accuracy of  test data W.R.T our trained data on the basis of proneness to heart attack. By using different type of scalers , I have also compared that which scaler gives maximum accuracy.
## About the Dataset
- Age : Age of the patient
- Sex : Sex of the patient
- cp : Chest Pain type chest pain type
 Value 1: typical angina
 Value 2: atypical angina
 Value 3: non-anginal pain
 Value 4: asymptomatic
- trtbps : resting blood pressure (in mm Hg)
- chol : cholestoral in mg/dl fetched via BMI sensor
- fbs : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
- rest_ecg : resting electrocardiographic results
     Value 0: normal
      Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or                                                     depression of > 0.05 mV)
      Value 2: showing probable or definite left ventricular hypertrophy by         Estes'criteria

- exang: exercise induced angina (1 = yes; 0 = no)

- thalach : maximum heart rate achieved
- target : 0= less chance of heart attack 1= more chance of heart attack






## Data set
![image](https://user-images.githubusercontent.com/77538080/213032384-23cb015b-acce-442f-8110-d83988898b4a.png)


## Training the data 
Using train test split package to split the data into training and testing models for further processing
## Scaling and it's purpose
Python Data Scaling – Standardization Data standardization is the process where using which we bring all the data under the same scale. This will help us to analyze and feed the data to the models. This is the math behind the process of data standardization.
## Scalers compared are 
![image](https://user-images.githubusercontent.com/77538080/213033054-3070a65f-2a98-4e7c-98b7-24c9c164a22a.png)
## Results
- We see that the optimal number of clusters that gives the highest accuracy is 7 which means that dividing the data into 7 clusters after scaling  down the data by using MinMax algorithm an accuracy of 90.1 can be achieved in the following data set

- By using the standard scaling algorithm , the optimal number of clusters is found to be 8 and an accuracy of 88.52 is achieved






