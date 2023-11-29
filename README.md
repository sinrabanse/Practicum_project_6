# Practicum_project_6
 My sixth project from Practicum course. "Business Analytics"

 What was used in the project: Python, Jupyter notebook. Libraries: pandas, numpy, plotly, matplotlib, seaborn.

# Project Description

I've been offered an internship in the analytical department at Yandex.Afisha. My first task is to help optimize marketing expenses.

I have:
 - Server logs with data on Yandex.Afisha visits from June 2017 through May 2018
 - Dump file with all orders for the period
 - Marketing expenses statistics

I'm going to study:
 - How people use the product
 - When they start to buy
 - How much money each customer brings
 - When they pay off

# Steps
1) Data preprocessing.
2) Make reports and calculate metrics:
   - Product:<br/>
        - How many people use it every day, week, and month?<br/>
        - How many sessions are there per day? (One user might have more than one session.)<br/>
        - What is the length of each session?<br/>
        - What's the user retention rate?<br/>
   - Sales:<br/>
        - When do people start buying?<br/>
        - How many orders do they make during a given period of time?<br/>
        - What is the average purchase size?<br/>
        - How much money do they bring? (LTV)<br/>
   - Marketing:<br/>
        - How much money was spent? Overall, per source and over time.<br/>
        - How much did customer acquisition from each of the sources cost?<br/>
        - How worthwhile where the investments? (ROI)<br/>
        
    Plot graphs to display how these metrics differ for various devices and ad sources and how they change in time.<br/>
3) Overall conclusion: advise marketing experts how much money to invest and where.

## Description of the data
#### The visits.csv table (server logs with data on website visits):

'Uid' — user's unique identifier<br/>
'Device' — user's device<br/>
'Start Ts' — session start date and time<br/>
'End Ts' — session end date and time<br/>
'Source Id' — identifier of the ad source the user came from

#### The orders.csv table (data on orders):

'Uid' — unique identifier of the user making an order<br/>
'Buy Ts' — order date and time<br/>
'Revenue' — Yandex.Afisha's revenue from the order

#### The costs.csv table (data on marketing expenses):

'source_id' — ad source identifier<br/>
'dt' — date<br/>
'costs' — expenses on this ad source on this day
     
