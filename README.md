# Business_Analytics


## Disclaimer: 
- This project is part of the Data Analyst training program from Practicum by Yandex. More info in link below:
https://practicum.yandex.com/profile/practicum100-da/ 
- The Data Sets are not open to the public therefore they are not included in this project


# Project Setup

You've done beautifully in the Practicum course, and you've been offered an internship in the analytical department at Yandex.Afisha. Your first task is to help optimize marketing expenses.

You have:
- Server logs with data on Yandex.Afisha visits from June 2017 through May 2018
- Dump file with all orders for the period
- Marketing expenses statistics

We are going to study:
- How people use the product
- When they start to buy
- How much money each customer brings
- When they pay off  

<br>            


# Description of the data

The `visits` table (server logs with data on website visits):
- Uid — user's unique identifier
- Device — user's device
- Start Ts — session start date and time
- End Ts — session end date and time
- Source Id — identifier of the ad source the user came from
*All dates in this table are in YYYY-MM-DD format.*

The `orders` table (data on orders):
- Uid — unique identifier of the user making an order
- Buy Ts — order date and time
- Revenue — Yandex.Afisha's revenue from the order

The `costs` table (data on marketing expenses):
- source_id — ad source identifier
- dt — date
- costs — expenses on this ad source on this day
