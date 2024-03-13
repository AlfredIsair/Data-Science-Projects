# E-Commerce Product Delivery Prediction

## Introduction
In this project, we conduct an analysis to understand the factors influencing on-time delivery in our e-commerce operations. We explore relationships between various aspects such as product properties, logistics operations, and customer experiences, and their impact on delivery performance. Our aim is to build predictive models using machine learning techniques to forecast delivery timelines accurately.

## Data Dictionary
The dataset contains the following information:

| Variable             | Description                                                |
|----------------------|------------------------------------------------------------|
| ID                   | ID Number of Customers                                     |
| Warehouse_block      | Warehouse block (A, B, C, D, E)                            |
| Mode_of_Shipment     | Shipment mode (Ship, Flight, Road)                         |
| Customer_care_calls  | Number of calls made for shipment inquiry                  |
| Customer_rating      | Customer rating (1=lowest, 5=highest)                      |
| Cost_of_the_Product  | Cost of the product (in US dollars)                        |
| Prior_purchases      | Number of prior purchases                                  |
| Product_importance   | Importance level of the product (low, medium, high)        |
| Gender               | Gender of the customer (Male, Female)                      |
| Discount_offered     | Discount offered on the product                            |
| Weight_in_gms        | Weight of the product (in grams)                           |
| Reached_on_Time_Y_N  | Target variable indicating whether the product reached on time (0=No, 1=Yes)|

## Key Relationships Explored
- Understanding the connection between customer distribution and delivery performance.
- Investigating the relationship between product features and delivery efficiency.
- Analyzing the interplay between logistics operations and delivery timeliness.
- Examining the impact of customer experience on delivery performance.

## Exploratory Data Analysis
We begin our analysis by exploring the dataset to uncover relationships between various factors and delivery performance. This involves visualizing distributions, correlations, and trends to gain insights into how different variables interact with each other.

## Conclusion
By examining customer behaviors and logistical details, we discover important insights into the factors influencing delivery times. With predictive models in hand, we can predict potential delays and take proactive measures to improve our operations, ultimately enhancing customer satisfaction.

## Usage
1. Clone the repository.
2. Open the notebook in Jupyter environment or any Python IDE.
3. Run the notebook cells sequentially.

## Libraries Used
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

