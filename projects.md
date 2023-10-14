---
title: "Projects"
disqus: false
---

When I began my data journey, it was like training a wild horse—an unpredictable yet thrilling experience. Starting with simple projects, I learned to clean and visualize data, much like grooming a young foal.

With growing expertise came tougher challenges, akin to breaking in a spirited colt. I wrangled complex datasets, corralled outliers, and rode the waves of statistical analysis, aiming to unveil insights for enlightened conclusions.

---

##  Email Report in Power BI

<iframe title="Email Report - finished" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiZmM1ZmZiMjMtNDZlZS00ZjJlLTllOWQtYzhhMjBkNWQzZjUyIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9" frameborder="0" allowFullScreen="true"></iframe>



In this project, I created a captivating email report dashboard using Power BI. The process involved designing visuals within Power BI and refining the design in Figma. I organized the data, including email addresses, subjects, countries, and timestamps, into a structured data model. The dashboard's objective was to provide insights into email volume trends, distribution between received and sent emails, average email count per week, and daily traffic patterns. I focused on making the report descriptive and visually appealing, emphasizing key metrics and trends through carefully crafted visualizations. The resulting dashboard offers a comprehensive overview of email activity, enhancing data-driven decision-making.

---

##  HR Analytics Dashboard in Power BI

<iframe title="Power BI HR Dashboard - Home" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiZTk3ZmI0YWMtODYwNS00NTI0LTljM2QtNjU5ODUwN2Y2MWI4IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9" frameborder="0" allowFullScreen="true"></iframe>

This dashboard is built from a 1470-row open HR dataset collected from Kaggle. It's a navigable report with three buttons to see the full HR insight.

---

## Investigate Medical Appointments

A person takes a doctor's appointment, receives all the instructions, and no-show. Who's to blame?
In this project, I will try to analyse why would some patient not show up for their medical appointment or whether there are reasons for that using the data we have. I will try to find some correlation betwen the different attributes and whether the patient shows up or not. The dataset I'm are going to use contains 110.527 medical appointments and its 14 associated variables ( PatientId, AppointmentID, Gender, ScheduledDay, AppointmentDay, Age, Neighbourhood, Scholarship, Hypertension, Diabetes, Alcoholism, Handcap', SMS_received, No-show )

### Questions to answer

*   What is the percentage of no-show?
*   What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?
    *   Is the time gender related to whether a patient will show or not?
    *   Are patients with scholarship more likely to miss their appointment?
    *   Are patients who don't recieve sms more likely to miss their appointment?
    *   Is the time difference between the scheduling and appointment related to whether a patient will show?
    *   Does age affect whether a patient will show up or not?
    *   What is the percentage of patients missing their appointments for every neighbourhood

#### After analyzing the dataset here are some findings:

1.  Percentage of patients who didn't show up for their appointment is 20.19%.
2.  The percentage of females missing their appointment is nearly two times the number of males. So females are more likely to miss their appointment.
3.  It appears that the longer the period between the scheduling and appointment the more likely the patient won't show up.
4.  It seems that patients with scholarships are actually more likely to miss their appointment.
5.  A strange finding here suggests that patients who received an SMS are more likely to miss their appointment !!
6.  There is no clear relation between the age and whether the patients show up or not but younger patients are more likely to miss their appointments.

#### Analysis Shortcoming & Data Limitations

*   The data doesn't state the exact hour of the appointment which would have been very useful to try to find out which hours have the most missing appointments and which doesn't. It could also be very useful to know the difference between scheduling and the appointment since many of the scheduling are on the same day.
*   The data doesn't state if any day is a vacation or not which can indicate if people tend to miss their appointments more on working days.
*   The age column had a negative value but according to the data creator, it means a baby not born yet (a pregnant woman).
*   When calculating the day difference between the scheduling and appointment days we had some negative value which makes no sense and might mean that the records of questions have wrong data.

Check the full project [here](https://nbviewer.org/github/zeidombo/investigate-medical-appointment/blob/master/investigate_medical_appointment.ipynb).

----

## Fraud and ID Theft Dashboard using Streamlit and Folium

In this project I built a python streamlit dashboard app that visualizes data in an interactive folium map. The dashboard is a remake of [*Fraud and Identity Theft Report*](https://public.tableau.com/app/profile/federal.trade.commission/viz/FraudandIDTheftMaps/AllReportsbyState) published by US Federal Trade Commission originally made with Tableau. I thought it might be challenging to replicate it with streamlit and it was time well spent.

<!-- ![Screenshot](./images/screenshot.png) -->

See a demo [here](https://zytaga-streamlit-folium-dashboard-streamlit-app-1all7m.streamlit.app) or visit my [github repository](https://github.com/zeidombo/streamlit-folium-dashboard) of the project.

---


## Forecasting the Weather Using Facebook's Prophet Algorithm

<!-- <iframe src="https://nbviewer.org/github/zeidombo/weather-forecast-using-facebook-prophet/blob/master/weather_forecast.ipynb" width="811" height="667">
</iframe> -->

In this project, I applied the Facebook Prophet algorithm to predict the weather in New York City using local weather data. Utilizing an additive model, Prophet combines seasonal effects and trends to make accurate predictions. The notable advantage of Prophet is its automatic detection of seasonality in the data, making it a suitable choice for weather data which typically exhibits strong seasonal patterns. This eliminates the need for extensive feature engineering, providing a solid baseline accuracy.

The project began with the collection and preparation of local weather data specific to New York City, which served as the foundational dataset for the forecasting model. Leveraging the Prophet algorithm, I analyzed the data and generated forecasts for future weather conditions in the city. Additionally, I explored the scalability of Prophet, demonstrating its capability to handle multiple time series effortlessly, including data from adjacent weather stations.

Overall, the project showcased the effectiveness of the Facebook Prophet algorithm in accurately predicting the weather, establishing it as a valuable tool for weather forecasting tasks, particularly in datasets characterized by distinct seasonal variations.

Check the full project [here](https://nbviewer.org/github/zeidombo/weather-forecast-using-facebook-prophet/blob/master/weather_forecast.ipynb).

---
If you have questions or comments about any of these projects, please feel free to [get in touch](/contact).
---