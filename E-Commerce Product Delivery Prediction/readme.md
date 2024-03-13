# E-Commerce Product Delivery Prediction

## Introduction
In this project, we are conducting an analysis to understand the factors influencing on-time delivery in our e-commerce operations. Specifically, we are exploring the relationships between various aspects such as product properties, logistics operations, and customer experiences, and their impact on delivery performance. Our aim is to build predictive models using machine learning techniques to forecast delivery timelines accurately.

## Key Relationships
- Understanding the Connection Between Customer Distribution and Delivery Performance
- Investigating the Relationship Between Product Features and Delivery Efficiency
- Analyzing the Interplay Between Logistics Operations and Delivery Timeliness
- Examining the Impact of Customer Experience on Delivery Performance

## Model Building
To gain insights and predict delivery times accurately, we use machine learning techniques. We preprocess our data, handle categorical variables carefully, and divide our dataset into training and testing subsets. We experiment with different algorithms, such as the Random Forest Classifier, Decision Tree Classifier, Logistic Regression, and K Nearest Neighbors. Through thorough tuning of hyperparameters, we aim to improve the performance of our predictive models.

## Conclusion
By examining customer behaviors and logistical details, we discover important insights into the factors influencing delivery times. With predictive models in hand, we can predict potential delays and take proactive measures to improve our operations, ultimately enhancing customer satisfaction.

## Data Dictionary
The dataset used contains the following information:

Variable | Description
--- | ---
ID | ID Number of Customers
Warehouse_block | The Company have big Warehouse which is divided into block such as A,B,C,D,E
Mode_of_Shipment | The Company Ships the products in multiple way such as Ship, Flight and Road
Customer_care_calls | The number of calls made from enquiry for enquiry of the shipment
Customer_rating | The company has rated from every customer. 1 is the lowest (Worst), 5 is the highest (Best)
Cost_of_the_Product | Cost of the Product in US Dollars
Prior_purchases | The Number of Prior Purchase
Product_importance | The company has categorized the product in the various parameter such as low, medium, high
Gender | Male and Female
Discount_offered | Discount offered on that specific product
Weight_in_gms | It is the weight in grams
Reached.on.Time_Y.N | It is the target variable, where 0 Indicates that the product has NOT reached on time and 1 indicates it has reached on time

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

## Author
[Your Name]


