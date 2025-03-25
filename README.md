# Airline Booking Dashboard

![Bookings and Services Dashboard](https://github.com/BalajiRamGanesh/Airline-Booking-Dashboard/blob/main/Bookings%20and%20Services%20Dashboard.png?raw=true)

![Travel Trends Dashboard](https://github.com/BalajiRamGanesh/Airline-Booking-Dashboard/blob/main/Travel%20Trends%20Dashboard.png?raw=true)

## Table of Contents
- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Dataset Description](#dataset-description)
- [Process](#process)
- [Insights](#insights)
- [Recommendations](#recommendations)

## Overview
This project explores airline booking data to uncover patterns in booking trends, service preferences, and travel behaviour. By analysing booking completion rates, extra service selections, and travel timings, the project aims to identify opportunities to improve the booking process and enhance the overall passenger experience.

## Problem statement
Understanding customer booking behavior is crucial for optimizing airline increasing booking completion rates. Many bookings remain incomplete and certain days of the week experience lower booking rates. This project aims to address key business questions:
- What percentage of passengers have confirmed bookings?
- What proportion of passengers opt for extra services?
- Which regions contribute most significantly to the total bookings?
- How do booking frequencies vary across different days of the week?
- During which time periods are most bookings completed?
- Which sales channels prove to be most effective in generating bookings?


## Dataset Description

 The dataset used in this project is available in [kaggle](https://www.kaggle.com/datasets/anandshaw2001/airlines-booking-csv) and also provided in this repository. This dataset contains 50,000 rows and 14 columns .
 

| Column| Description|
|-------|-------------|
|num_passengers | Number of passengers|
|sales_channel | Platform used for booking |
|trip_type | The type of trip booked(round trip, one way, circle trip) |
|purchase_lead | The number of days between the booking date and the departure date|
|length_of_stay |The number of days spent at destination|
|flight_hour | The departure hour of the flight in 24hour format
|flight_day | The departure day of the week |
|route | The route of the flight from origin to destination
|booking_origin | The country where booking is made|
|wants_extra_baggage | Indicates if the passengers require extra baggage|
|wants_preferred_seat | Indicates whether passengers are selecting prefered seats|
|wants_in_flight_meals | Indicates if the passengers require flight meals|
|flight_duration |The travel duration between origin and destination |
|booking_complete | Indicates whether the bookings is completed or incomplete|

## Process

1. **Data Import:** Imported the raw dataset into Power BI.  
2. **Data Transformation:** Converted binary values into meaningful category labels for better readability.  
3. **DAX Implementation:** Created new measures and a calculated column using DAX to enhance data insights.  
4. **Dashboard Creation:** Designed two dashboards for airline bookings. The first dashboard explores bookings and services, while the second focuses on travel trends.  

## Insights 
- Only 14.9% of bookings are completed, and 15.5% of passengers have confirmed their bookings, indicating a high rate of incomplete or abandoned bookings.
- A significant proportion of passengers opt for extra services: 36.7% select preferred seats, 47% request flight meals, and 22.1% require extra baggage.
- The majority of bookings originate from Australia, Asia, and Europe.
- Friday, Saturday, and Sunday receive fewer bookings compared to other days of the week.
- Most passengers travel on a limited number of routes.
- A large proportion of passengers stay less than 40 days at their destination.
- The highest booking completion rates occur between midnight and evening.
- The majority of bookings are sold through the roundtrip sales channel.

## Recommendations

- **Improve user experience and simplify the booking process** by enhancing the website design and sending reminder emails to passengers about their incomplete bookings. 
- **Encourage more passengers to opt for extra services** by promoting special deals on preferred seats, flight meals, and extra baggage.  
- **Increase weekend bookings** by providing discounts on Friday, Saturday, and Sunday to attract more passengers on these lower traffic days.  
- **Encourage early return bookings** by offering discounts for passengers who book their return flights in advance, as many tend to return within a few days.  


