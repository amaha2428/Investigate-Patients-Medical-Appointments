# Investigate Medical Appointments No shows


## project overview
The aim of this project is to investigate on why a person makes a doctor appointment, receives all the instructions and no-show. The dataset used contains informations of over 100k medical appointments in Brazil. The analysis is focused on getting insights from the data as which of the features play a role if a patient turn up or not for his/her medical appointment.

Here are links to the resources used:
- https://s3.amazonaws.com/video.udacity-data.com/topher/2018/July/5b57919a_data-set-options/data-set-options.pdf
- https://www.kaggle.com/datasets/joniarroba/noshowappointments

This project was completed as part of my Udacitys [Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002) certification

## Details
There were some quality issues with the dataset that needed to be fixed which i did. Some of the issues include wrong data types and inappropriate observations. After making necessary data cleaning, i then got insights from the dataset by investigating individual features as well as combining features. Some of the questions i answered include:
1. Neighbourhood with most situated hospital
2. What gender had the most appointment
3. Did patients show up or not
4. Does sending of messages affect patients appointment?
5. Could there be patients with more than one appointment? 

## Findings

**From our analysis, we can see that:**
1. Alot of very young people are featured on this dataset with majority of them at age zero(0).
2. 25% of patients are below 18yrs, on average a patient age is 37yrs and majority of patient are below 55yrs.
3. Most of the patients are not Alcoholic, Diabetic and also, most of them do not have Hypertension.
4. 20% of appointments were missed by patients.
5. in regards to sms sent, most of the patient who showed up for their appointment didnt receive any sms.
6. Majority of patients are not enrolled in Brasilian welfare program Bolsa Família
7. The dataset is made up of 64% female.

**Limitations:**

1. The total number of patients who showed up for appointment is 88207 which is which makes up 80% of data. 
This shows already that we have an imbalanced dataset and when we decide to build a machine learning model with it,
our model will learn more from the dominat class which will may lead to inaccurate predictions from our model.

2. Majority of patients who missed an appointment actually received SMS from the hospital but we cannot say when 
those messages was sent. We do not know if those messages were sent days, weeks or months before the day of 
appointment. As this could play a role as to why patients do not show up.


## Tools/Libraries
python, pandas, seaborn, Matplotlib
