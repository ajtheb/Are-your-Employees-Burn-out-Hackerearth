# Are-your-Employees-Burn-out-Hackerearth
Problem link -
https://www.hackerearth.com/problem/machine-learning/predict-the-employee-burn-out-rate-7-6340b4e3/

Problem Statement

World Mental Health Day is celebrated on October 10 each year. The objective of this day is to raise an awareness about mental health issues around the world and mobilise efforts in support of mental health. According to an anonymous survey, about 450 million people live with mental disorders that can be one of the primary causes of poor health and disability worldwide.
You are a Machine Learning engineer in a company. You are given a task to understand and observe the mental health of all the employees in your company. Therefore, you are required to predict the burn out rate of employees based on the provided features thus helping the company to take appropriate measures for their employees.

My Solution to the machine learning hackathon Are your Employees Burn out?

<b>2nd rank</b> on public leaderboard

The two models used for submission are Catboost Regressor and Lightgbm with the ratio 2:1 for making ensemble submission.

The features used are-

'WFH Setup Available' , 'Designation', 'Resource Allocation','Mental Fatigue Score', 'Designation_res', 'des_gen_mfs','gen_wfh_mfs','Mfs/des', 'Mfs/res','experience'

The features different from dataset-

'Designation_res' is concatenation of Designation and Resource allocation which makes good differentiating categories for burn rate.

'des_gen_mfs' is an aggregating feature for mean mental fatigue score grouped by designation and Gender.

'gen_wfh_mfs' is an aggregating feature for mean mental fatigue score grouped by Gender and work from home available.

'Mfs/des' is Mental Fatigue Score / (Designation+1)
   
'Mfs/res' is Mental Fatigue Score / (Resource Allocation+1)

'experience' the duration of job since date of joining. 
