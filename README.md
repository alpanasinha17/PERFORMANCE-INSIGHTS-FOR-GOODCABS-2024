# PERFORMANCE-INSIGHTS-FOR-GOODCABS-2024

Provide Insights to Chief of Operations in Transportation Domain
This Project is part of CodeBasics Resume Challenge 13.

## Video Presentation Link: 

This repository includes the code, datasets, and insights from my analysis for **Performance Insights for Goodcabs 2024**  

**Problem Statement**

Goodcabs, a cab service focusing on Tier -2 cities in India, has been in operation for 2 years and supports local drivers while providing excellent service to passengers. The company aims to achieve ambitious 2024 targets by analyzing its performance on key metrics like trip volume, passenger satisfaction, repeat passenger rates, and the balance between new and repeat passengers.
The Chief Operations, Bruce Haryali, urgently needs insights on these metrics. However, the analytics manager, Tony is busy with another project and assigned this task to Peter Pandey, a curious data analyst. Peter will prepare the insights using notes provided by Tony, as these findings will directly impact decision - making the leadership level.

**TASK**
My task is to analyze Goodcabs performance metrics, identify key insights, and provide actionable recommendations to help the company meet its 2024 goals for growth and passenger satisfaction.

**Business Request**

*Business Request -1: City-Level Fare and Trip Summary Report*

Generate a report that displays the total trips, average fare per km, average fare per trip, and the percentage contribution of each city's trips to the overall trips. This report will help in assessing trip volume, pricing efficiency, and each city's contribution to the overall trip count.

Fields:

• city_name
• total_trips
• avg_fare_per_km
• avg_fare_per_trip
• %_contribution_to_total_trips

![image](https://github.com/user-attachments/assets/d7c05778-0a55-4070-b1df-da66faa417ed)

*Business Request -2: Monthly City-Level Trips Target Performance Report*

Generate a report that evaluates the target performance for trips at the monthly and city level. For each city and month, compare the actual total trips with the target trips and categorise the performance as follows:

• If actual trips are greater than target trips, mark it as "Above Target".
• If actual trips are less than or equal to target trips, mark it as "Below Target".

Additionally, calculate the % difference between actual and target trips to quantify the performance gap.

Fields:

• City_name
• month name
• actual_trips
• target_trips
• performance_status
• % difference
![image](https://github.com/user-attachments/assets/4122c6d2-b0e6-4c5f-b8e9-7fae38f5709b)
![image](https://github.com/user-attachments/assets/3aee0277-af98-4e7d-b8af-fcef3b16654b)
![image](https://github.com/user-attachments/assets/650a72ce-4a13-46bc-8a00-287a63e8f86f)

*Business Request - 3: City-Level Repeat Passenger Trip Frequency Report*

Generate a report that shows the percentage distribution of repeat passengers by the number of trips they have taken in each city. Calculate the percentage of repeat passengers who took 2 trips, 3 trips, and so on, up to 10 trips.

Each column should represent a trip count category, displaying the percentage of repeat passengers who fall into that category out of the total repeat passengers for that city.

This report will help identify cities with high repeat trip frequency, which can indicate strong customer loyalty or frequent usage patterns.

• Fields: city_name, 2-Trips, 3-Trips, 4-Trips, 5-Trips, 6-Trips, ?-Trips, 8-Trips, 9-Trips, 10-Trips


![image](https://github.com/user-attachments/assets/f94f64a1-5096-45e8-a8d3-c213223df6f4)

*Business Request -4: Identify Cities with Highest and Lowest Total New Passengers*

Generate a report that calculates the total new passengers for each city and ranks them based on this value. Identify the top 3 cities with the highest number of new passengers as well as the bottom 3 cities with the lowest number of new passengers, categorising them as "Top 3" or "Bottom 3" accordingly.

Fields

• city_name
• total_new_passengers
• city_category ("Top 3" or "Bottom 3")
![image](https://github.com/user-attachments/assets/baf19326-193d-46b5-8192-b6d119a480b1)

*Business Request - 5: Identify Month with Highest Revenue for Each City*

Generate a report that identifies the month with the highest revenue for each city. For each city, display the month_name, the revenue amount for that month, and the percentage contribution of that month's revenue to the city's total revenue.

Fields

• city_name
• highest_revenue_month
• revenue
• percentage_contribution (%)
![image](https://github.com/user-attachments/assets/19bdaec8-4826-4f01-8979-94895920e5a6)

*Business Request - 6: Repeat Passenger Rate Analysis Generate a report that calculates two metrics:*

1. Monthly Repeat Passenger Rate: Calculate the repeat passenger rate for each city and month by comparing the number of repeat passengers to the total passengers.
2. City-wide Repeat Passenger Rate: Calculate the overall repeat passenger rate for each city, considering all passengers across months.

These metrics will provide insights into monthly repeat trends as well as the overall repeat behaviour for each city.

Fields:

• city_name
• month
• total_passengers
• repeat_passengers
• monthly_repeat_passenger_rate (%): Repeat passenger rate at the city and month level
• city_repeat_passenger_rate (%): Overall repeat passenger rate for each city, aggregated across months

![image](https://github.com/user-attachments/assets/b278f868-ef99-4767-b9cf-1fcbbb1fd1ea)
![image](https://github.com/user-attachments/assets/1c2bcb23-ce06-4c1f-9031-5788416a2606)
![image](https://github.com/user-attachments/assets/d5fd57a0-ca7a-4335-b892-9deaaad0f5fa)

**Tools Used**
  Advance Excel
  MY SQL
  




