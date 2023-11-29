# No-show-navigation
# Brief Summary:
A hospital is facing issues with patients not showing up for their scheduled appointments. The no-shows are causing scheduling issues and financial losses. 
The goal is to identify patterns and factors contributing to patients missing their appointments in order to predict whether a patient will show up for their appointment.
# Data: 
Data source: Kaggle <br> Sample size: (110527 rows, 14 columns)<br> Time period: 2016 <br>Data alterations: 
Introduced new feature called ‘Waiting Time’ in order to understand the impact/contribution of the time patients had to wait until the Appointment day.
Excluded rows with negative ‘Waiting Time’ values.
# Features: 
The features ‘Hypertension’ and ‘Age’ appeared to be strongly co-related with the number of No-shows as per the plots.Evidently, the people between ages 50 and 80 suffer from hypertension. This relationship can substantially prove to be one of the factors leading to No-shows. 
<br> The ‘No-show’ ratio overall is 28.5%  and one of the first features to explore was ‘Neighbourhood’.
The locality ‘JARDIM CAMBURI’ was found to be the one with the highest number of No-Shows among all the neighbourhoods. <br> 

# Modeling methods:
### The machine learning model implemented is Random Forest
Our outcome variable is 'Will patients show up'? Our goal is to predict whether a patient will attend their scheduled medical appointment. This helps us in better scheduling and resource management, ensuring efficient healthcare delivery.<br>

# Findings: 
### Accuracy: Overall, Success Rate: 
About 63% Accuracy. Our model correctly predicts whether patients will show up for their appointments about 63% of the time.<br>
### Precision: A closer look
For Patients Showing Up (Class 0):<br>
Precision (75%): When our model predicts a patient will show up, it's correct 75% of the time. <br>
For Patients Not Showing Up (Class 1):<br>
Precision (36%): When our model predicts a no-show, it's correct about 36% of the time.<br>
What This Tells Us: We're better at predicting who will show up than who won't. This finding is crucial for planning and managing our healthcare resources effectively.
# Connection to the Business need:
Accurately predicting no-shows is crucial for better scheduling and resource allocation in our healthcare services.<br>
Incorrectly predicting no-shows can lead to underutilization of resources and missed opportunities to serve more patients. <br>
### Actionable Recommendation:
Develop targeted strategies to engage with patients flagged as potential no-shows, including reminder systems, flexible rescheduling options, or transportation support to encourage attendance.



