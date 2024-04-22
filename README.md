<h1 align = "center" style = "font-weight : bold">
Swire Coca Cola Capstone Project
</h1>
![download](https://github.com/ssreemutyapu/Swire-Coca-cola-capstone-project/assets/153456790/ada3448c-b9bd-4602-89d9-362de14c1e3e)



## **Introduction:**
Swire Coca-Cola is dedicated to staying ahead of consumer trends by continuously introducing innovative products to the market. These unique offerings, marked by premium pricing, not only expand the company's market reach but also attract new customers. However, optimizing production planning and inventory management for these novel beverages presents a significant challenge. Swire aims to accurately forecast demand for its new products to ensure optimal production quantities, prevent stockouts and overproduction, minimize costs, and maximize customer satisfaction. 
To address this, our project focuses on developing forecasting models to predict the weekly demand for seven upcoming innovation products. By leveraging historical data and key product attributes such as caloric segment, market category, manufacturer, brand, package type, and flavor, we aim to provide Swire with actionable insights and tools to drive revenue growth and sustain long-term success in a dynamic market landscape.

## **Business Problem:**
Swire Coca-Cola is consistently rolling out innovative products and aims to enhance its production planning and inventory management for these new beverages. The challenge lies in accurately forecasting the demand for these products to optimize production quantities, prevent stockouts and overproduction, reduce costs, and enhance customer satisfaction. This project seeks to precisely predict the weekly demand for these innovative products, with a focus on optimizing production, minimizing costs, ensuring customer satisfaction, and predicting market location and dates.

## **Project Objective:**
The Project objectives align with Swire Coca-Cola's goal of staying ahead of consumer trends, expanding market reach, and optimizing production planning and inventory management for innovative products.
1. Develop forecasting models to accurately predict the weekly demand for seven upcoming innovation products introduced by Swire Coca-Cola.
2. Utilize historical data and key product attributes such as caloric segment, market category, manufacturer, brand, package type, and flavor to enhance the accuracy of demand forecasts, aiming to prevent stockouts and overproduction while minimizing costs.
3. Continuously update forecasting models based on new data to improve forecast accuracy and adapt to changing market dynamics, sustaining long-term success in a dynamic market landscape.

## **Your group's solution to the Business Problem.**
Our group's solution to Swire Coca-Cola's business problem involves implementing the Prophet model as the optimal forecasting solution. This decision stems from its capability to produce the lowest Mean Absolute Percentage Error (MAPE) compared to alternative models. With Prophet, we generate comprehensive demand forecasts for innovative products, considering specific country trends, seasonality, and holiday effects. Furthermore, we've developed a custom function to refine trend and seasonality components, tailoring them to each product model's unique parameters.

By utilizing this machine learning model, we can continually update sales forecasts for upcoming weeks, enabling Swire to make informed decisions regarding product continuation or discontinuation in the market. Additionally, our model effectively addresses queries about the ideal 13-week period and optimal holiday season for product launches. Overall, the Prophet model's low MAPE values indicate its proficiency in accurately predicting sales, especially when data is filtered to resemble characteristics of new innovation drinks.

## **Your Contribution to the Project**
In the Swire Coca-Cola project, I played a crucial role from the outset, focusing on data preprocessing and feature engineering. I spearheaded collaboration efforts by organizing regular meetings to enhance our dataset understanding, where I assigned tasks to team members, ensuring everyone remained on track throughout the project. Transitioning to exploratory data analysis (EDA), I concentrated on extracting and analyzing datasets, beginning with comprehensive data preprocessing. I delved into various aspects of the data, such as the impact of categories on unit sales and analyzing Segment and Zip code fields, presenting insightful visuals to illustrate targeting strategies across different products and years. 

My efforts extended into the modeling phase, where I untangled dataset complexities and provided essential context. Initiating the modeling process involved comprehensive data exploration and the application of AR and ARIMA techniques to analyze UNIT_SALES performance. Through meticulous data filtering and analysis, I identified key periods of heightened demand, offering actionable insights into consumer behavior and facilitating informed decision-making processes for the team.

## **The Business value of the Solution.**
The business value of the solution with a remarkable MAPE value of just 9.38%, the Prophet model shows considerable effectiveness in predicting future innovative items. This means that over 90% of the time, the predicted values agree with the true positives. More specifically, the MAPE for the initial innovation product with plum flavoring is about 29%, which translates to a 70% forecast accuracy rate. But the MAPE values for the second and third innovation products, which feature avocado and kiwano flavors, respectively, are much lower at about 10%, indicating an astounding 90% accuracy in forecasting for both.

In addition to the accuracy percentages, our study provided insightful answers to relevant concerns, such identifying the best 13-week windows for product debuts and predicting demand patterns for particular holidays, like Easter. Sales predictions for the avocado product. This allowed Swire to adjust production estimates and reduce the danger of under or overproduction, successfully minimizing operating costs.

## **Difficulties that your group encountered along the way.**
Our biggest challenge was handling the large amount of data, which required a lot of processing power to read and process inside of Python notebooks. In order to address this, we retrieved only the pertinent data from Excel, BigQuery and used SQL coding to make the necessary changes to the data. Therefore, during our exploratory data analysis (EDA) phase, we faced difficulties navigating data quality concerns, comprehending column distributions, and correcting missing values. Nonetheless, the EDA notebook successfully addressed these challenges.

Moreover, during model building, it was difficult to deal with complex time-series patterns, such as holidays and seasonal variations. Lastly, iterative testing was necessary to choose and fine-tune forecasting models like Random Forest, XGBoost, ARIMA, SARIMA and Prophet in order to maximize performance. This was especially true given the complex nature of sales data for innovative items for which direct historical data was unavailable.

## **What you learned in the project.**
The project gave me a great opportunity to learn and grow, improving both our technical and teamwork capabilities. It emphasized how crucial it is to manage real-world datasets skillfully and how careful data cleaning and pretreatment are necessary to guarantee data integrity. Investigating other time series forecasting methods, such as XGBoost, ARIMA, SARIMA, and Prophet, strengthened our understanding of this field by offering profound insights into identifying and forecasting complex sequential patterns.

The ability to solve problems was sharpened by tackling difficulties like model selection and data integration, which also highlighted the importance of being flexible in response to changing project requirements. In order to produce a unified project end, effective cooperation was essential, emphasizing the need for coordinated efforts, clear communication, and integration of varied contributions. We were more adept at bridging the gap between technical and non-technical audiences and highlighting the significance of effective communication by presenting findings to stakeholders. All things considered, the project promoted a thorough educational experience in the field of data analytics, emphasizing teamwork, flexibility, and a business-oriented approach.
