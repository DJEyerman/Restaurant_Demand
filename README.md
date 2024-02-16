# Restaurant Delivery & Satisfaction Project

## Objective:
The primary objective of this data analytics project was to enhance the customer experience in online food ordering by optimizing delivery operations. This involved conducting delivery analytics to ensure efficient staff availability, monitor key performance indicators (KPIs), and perform in-depth analysis of customer behavior and restaurant characteristics.


## Data Sources:
    • Order Records: Collect detailed information about each food order, including timestamp, order ID, 
    customer details, restaurant details, order items, quantity, and total cost.
    • Delivery Logistics: Capture data related to the delivery process, including delivery times, 
    delivery personnel details, and any delays or issues encountered during the delivery.
    • Customer Feedback: Incorporate customer reviews, ratings, and feedback on both the food 
    items and the overall delivery experience. This qualitative data provides insights into 
    customer satisfaction and areas for improvement.


## Exploratory Data Analysis (EDA): 

In the initial phase of the project, Exploratory Data Analysis (EDA) was conducted to unlock meaningful patterns and insights within the dataset. This involved cleaning and preprocessing the data, analyzing temporal and customer behaviors, and assessing the impact of promotional campaigns. The goal is to glean actionable insights through visualizations and statistical analyses, paving the way for informed decision-making in subsequent project stages.

During the EDA work, several interesting patterns were seen including the following. 

The number of orders by cuisine type shows that the four (4) cuisines that have the most orders: American, Japanese, Italian, and Chinese.  


![Popular_Cuisine](https://github.com/DJEyerman/Restaurant_Demand/assets/38670302/8bc7ff77-db70-41c1-9f35-91f791bf41d1)


The review also found the cost of the order to be around 11 to 12 dollars: 


![Cost_of _Order](https://github.com/DJEyerman/Restaurant_Demand/assets/38670302/f4587f0d-feec-401a-bee4-75682e910f8b)


The total time to prepare and deliver order is between 48 and 55 minutes: 

![Total_Time](https://github.com/DJEyerman/Restaurant_Demand/assets/38670302/dccaca26-58fa-4abd-b625-9e2fcf5d30ad)


One interesting point seen during EDA was the number of repeat customers.  While people did place a second order with a restaurant, they rarely place a third or more orders with the same restaurant. This is important as repeat customers are a key to the overall success of a restaurant.  

![Repeat_Orders](https://github.com/DJEyerman/Restaurant_Demand/assets/38670302/dc485d1d-6b67-4fd2-8851-3471b1306786)


## Data Preprocessing:
As there were not any null values in the data and no real outliers, data preprocessing was not required.  

Data preprocessing is typically conducted to handle and mitigate issues such as missing values, outliers, and inconsistencies within a dataset, ensuring that it is suitable for analysis and modeling. However, when dealing with a complete dataset—meaning it contains no missing values or outliers, and all data points are accurate and consistent—extensive preprocessing might not be necessary.  In such cases like this, the dataset is considered "clean" and "ready for analysis" from the outset.


## Dashboard Creation in Tableau:
In Tableau, a dynamic and user-friendly restaurant and customer dashboard was created, bringing together crucial insights into revenue, profits, and restaurant ratings. The dashboard seamlessly integrates financial metrics, providing a real-time overview of revenue and profits, and incorporates customer ratings to gauge overall satisfaction. Through interactive visualizations, stakeholders can easily track performance trends, make data-driven decisions, and enhance the overall customer experience in the cuisines and restaurants.


![Dashboard](https://github.com/DJEyerman/Restaurant_Demand/assets/38670302/4002b300-fcc1-4a50-8e4e-1a2c53b02caf)

## Visualization and Metrics Comparison in Python:

In this project, Python's capabilities for Visualization and Metrics Comparison are leveraged, providing a clear lens into the project's dynamics. Through engaging visualizations using Matplotlib and Seaborn, patterns in delivery routes, customer behavior, and menu popularity are illuminated. Python's statistical tools enable metric comparisons, from revenue trends to delivery efficiency, offering actionable insights for strategic decision-making. Interactive dashboards crafted with Tableau enhance user exploration, while integration with Jupyter Notebooks ensures transparency and reproducibility in the data analysis.

The power of data visualization is leveraged to gain valuable insights. A compelling scatterplot has been crafted, revealing a nuanced relationship between the number of repeat orders and the sum of orders for our diverse customer base. This visual representation not only showcases customer loyalty through repeated engagements but also highlights the cumulative value generated from these loyal patrons. Analyzing this scatterplot provides a strategic lens, allowing us to tailor retention strategies and enhance the overall customer experience in our food delivery ecosystem.


![Scatterplot](https://github.com/DJEyerman/Restaurant_Demand/assets/38670302/ca0623ff-9277-47ad-8dff-3343464f1fff)

The visual prowess of histograms is employed to illuminate the distribution of repeat orders within the customer base. This impactful histogram showcases the count of repeat orders, providing a clear understanding of customer loyalty trends. Additionally, the histogram encapsulates the repeat percentage of orders, offering insights into the prevalence of repeat business. This visual representation serves as a strategic compass, guiding us in refining customer retention strategies and fostering long-term relationships in the dynamic landscape of food delivery.



![histogram](https://github.com/DJEyerman/Restaurant_Demand/assets/38670302/fb70538b-9696-46db-92af-cb14d590c4ea)


## Conclusions: 
    • The top four cuisine types getting the most orders are:
        ◦ American
        ◦ Japanese
        ◦ Italian
        ◦ Chinese
        ◦ Together they account for 82.56% of all orders.
    • The cuisine types with the least orders are:
        ◦ Southern
        ◦ Korean
        ◦ Spanish
        ◦ Vietnamese
    • %71.18 of orders happen during the weekends
    • The majority of orders are between roughly 11 and 23 dollars.
    • Approximately 30% of orders cost more than 20 dollars
    • The majority of revenue comes from orders between 5 and 20 dollars
    • The average time to prepare and deliver an order is 52 minutes
        ◦ Average of 24 minutes to prepare an order
        ◦ Average 27 minutes to deliver it
    • 60% of delivery customers say timeliness is a key factor to their satisfaction 
    • The cuisine type with longest time to prepare and deliver an order are the same as the ones 
    getting the most orders
    • If there are repeat customers, they usually repeat 2 to 4 times with the majority (%69)
    repeating only 2 times
    

## Recommendations:
    • Work on getting the time to prepare and deliver an order to between 35 and 40 minutes
        ◦ 30 minutes is the national standard
        ◦ It should take 10 to 15 minutes to prepare an order
        ◦ It should not take over 15 minutes to deliver an order
    • Start by working on the top four cuisine types getting the most orders:
        ◦ American
        ◦ Japanese
        ◦ Italian
        ◦ Chinese
    • Add drivers on weekends when demand is the highest
    • Consider restricting delivery area to speed the delivery time time
    • Work with the restaurant partners to improve food preparation time
    • Consider dropping the cuisine types with the least orders:
        ◦ Southern 17 orders
        ◦ Korean 13 orders
        ◦ Spanish 12 orders
        ◦ Vietnamese 7 orders
    • Work on increasing the number of repeat customersrepeat customers


## Business Impact: 
The project has fundamentally transformed the customer experience in online food ordering by harnessing the power of data analytics to optimize delivery operations. Through meticulous delivery analytics, staff availability has been streamlined, critical key performance indicators (KPIs) have been monitored, and in-depth analyses of both customer behavior and restaurant characteristics have been conducted. This strategic approach has not only ensured timely and efficient deliveries but has also resulted in a profound impact on customer satisfaction and loyalty. By aligning operations with data-driven insights, the efficiency of our delivery services has been enhanced, but the overall online food ordering experience for our valued customers have been elevated, driving sustained growth and positive brand perception.


## Future Work:
    • Add weather data to the analysis to determine if/how weather is affecting 
    delivery times
    • Add time of day to the orders to determine when the majority of orders are placed 
    on the weekends
    • Add geographic data to determine what areas of the city generate the most orders
    • Perform a deeper drive on the top four cuisine types to determine exact cost 
    and profit for the deliveries
    • Perform sentiment analysis on customer rating and reviews
