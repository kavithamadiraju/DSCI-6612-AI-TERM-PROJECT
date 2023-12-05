# DSCI-6612-AI-TERM-PROJECT

Introduction :
Sepsis is a life-threatening organ failure caused by an abnormal host response to infection. This can be ascribed in part to difficulties in detecting sepsis early and initiating timely and adequate therapy. A major barrier to early detection is distinguishing sepsis from sickness symptoms (e.g., inflammation) that have similar clinical signs (e.g., change in vitals), symptoms (e.g., fever), and molecular manifestations (e.g., dysregulated host response). 

Project Goal:
The main objectives of this project are: 
•	To study the various existing methods used in the literature for early detection of sepsis. 
•	To propose an efficient classification model for early prediction of sepsis. 
•	To analyze the proposed system with state-of-art existing algorithms. 
•	To increase the accuracy of the prediction model.
The inputs are patients' information, including vital signs, laboratory values and body demographics.
 
 Dataset :
 For this study, we use clinical data of ICU patients from two separate hospital systems provided by the PhysioNet Computing in Cardiology Challenge 2019.
 Data used in the competition is sourced from ICU patients in three separate hospital systems. Data from two hospital systems will be publicly available; however, one data set will be censored and used for scoring. The data for each patient will be contained within a single pipe-delimited text file. Each file will have the same header and each row will represent a single hour's worth of data. Available patient co-variates consist of Demographics, Vital Signs, and Laboratory values.
 
 Code :
 Our code are in four folders: 
 data_analysis_sepsis1(1).ipynb
 dealing with imbalance dataset.ipynb
 feature engineering.ipynb
 decision tree implementation-1.ipynb
 
 Results :


Exploratory Data Analysis
![image](https://github.com/kavithamadiraju/DSCI-6612-AI-TERM-PROJECT/assets/150641777/8a61dd2e-6ea0-4679-85d5-f1218c091264)

Pair plot(a)
![image](https://github.com/kavithamadiraju/DSCI-6612-AI-TERM-PROJECT/assets/150641777/aafc7fc7-5253-4464-a31b-756b5f8931bb)

Pair Plot(b)
![image](https://github.com/kavithamadiraju/DSCI-6612-AI-TERM-PROJECT/assets/150641777/e116328a-7dc2-4250-b2c1-dd4a39bf8981)

Pair Plot(c)
![image](https://github.com/kavithamadiraju/DSCI-6612-AI-TERM-PROJECT/assets/150641777/e54a3f53-7aa2-415d-a2cc-3c1906848689)

Pair Plot(d)
![image](https://github.com/kavithamadiraju/DSCI-6612-AI-TERM-PROJECT/assets/150641777/5cec37da-bff6-4563-8848-500f69085ea1)

Output of Decision Tree
![image](https://github.com/kavithamadiraju/DSCI-6612-AI-TERM-PROJECT/assets/150641777/7a37ce82-06a8-4e0f-9d51-1a961437955e)








