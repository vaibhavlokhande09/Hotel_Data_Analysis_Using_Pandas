# Hotel_Data_Analysis_Using_Pandas
Problem Statement:
Atiliq Grant is a hotel chain with properties located in different cities in India, primarily in Delhi, Mumbai, Bangalore, and Hyderabad. The hotels are categorized into four different categories: seasons, exotica, bay, and palace. Each category offers different types of rooms, namely standard, elite, premium, and presidential. The bookings made by customers are stored in a bookings database. However, due to intense market competition, Atiliq Grant has been experiencing a decline in both customer retention and revenue. Our task is to perform data analysis and generate valuable insights that can help Atiliq Grant improve their revenue.

Steps:

1. Understanding the Business Problem:
The first step in addressing the business problem faced by Atiliq Grant is to gain a comprehensive understanding of the challenges they are currently facing. This involves identifying the factors contributing to the decline in customer retention and revenue. By analyzing the market competition and customer preferences, we can develop a clear understanding of the issues at hand.

2. Data Collection and Cleaning:
To perform data analysis, it is crucial to collect relevant data from various sources, such as the bookings database. This data may include information about customer bookings, hotel categories, room types, and revenue generated. Once the data is collected, it needs to be cleaned to ensure accuracy and consistency. This involves removing any duplicate or irrelevant entries, correcting errors, and standardizing the data format.

3. Data Exploration:
After the data has been cleaned, the next step is to explore and analyze it. This involves examining the relationships between different variables, identifying patterns, and uncovering any hidden insights. By visualizing the data through charts, graphs, and statistical measures, we can gain a deeper understanding of the factors influencing customer retention and revenue.

4. Data Transformation:
In order to generate meaningful insights, it may be necessary to transform the data. This can involve aggregating the data at different levels, such as by hotel category, room type, or city. Additionally, variables may need to be transformed or combined to create new metrics that better capture the underlying trends and patterns. By transforming the data, we can uncover valuable insights that were not apparent in the raw data.

5. Collecting Insights:
The final step is to collect and present the insights derived from the data analysis. These insights should provide actionable recommendations to help Atiliq Grant improve their revenue. This may include identifying the most profitable hotel categories or room types, understanding customer preferences and behavior, and suggesting strategies to enhance customer retention. By presenting these insights in a clear.


Understanding Data - 
We possess 4 dimension tables and 2 fact tables.

1. dim_hotels - This table contains data on all hotels, including columns such as property_id, property_name, category, and city.

2. dim_rooms - This table contains information about room_id and room_category.

3. dim_date - This table serves as a calendar dimension, providing details such as date, mm-yy, week_no, and day_type (weekend or weekday).

4. fact_bookings - This is the main transactional table that holds data on bookings. It includes columns such as booking_date, property_id, check-in date, checkout date, number of guests, booking platform, revenue generated, and revenue realized.

5. fact_aggregated_bookings - This table contains aggregated data, presenting aggregated values for bookings and capacity. It includes columns such as property_id, check-in date, room_category, successful_bookings, and capacity.

Insights Generated - 
1. Determine the average occupancy rate for each room category.
2. Calculate the average occupancy rate per city.
3. Identify whether occupancy is higher on weekdays or weekends.
4. Analyze the occupancy for different cities in June.
5. Evaluate the revenue realized per city.
6. Examine the revenue month by month.
7. Assess the revenue realized per hotel type.
8. Calculate the average rating per city.
9. Determine the revenue generated using a particular platform.
