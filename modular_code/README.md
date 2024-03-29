
# Project Title: E-Commerce Purchase Probability Prediction

## Background
Our client, an early-stage e-commerce company, offers a wide range of products from daily essentials to high-end electronics. Despite a high volume of traffic, the conversion rate from browsing to purchasing remains low. To address this, the client aims to implement a targeted discount campaign but has limited funds. Therefore, they seek to predict the purchase probability of each user to optimize the allocation of discounts and coupons.

## Objectives
- **Primary Objective**: To build a model that predicts the purchase probability of each user, enabling targeted discount campaigns.
- **RFM Analysis**: Conduct a detailed RFM (Recency, Frequency, Monetary) analysis to segment users based on their purchase behavior.
- **Propensity Modeling**: Use propensity modeling to forecast user behavior and identify users who require incentives to make a purchase.

## Data Description
The dataset provided by the company includes the following features:
- `User_id`: Unique identifier for each user.
- `Session_id`: Unique identifier generated every time a user visits the platform.
- `DateTime`: Timestamp indicating when an action is performed by the user.
- `Category`: The category of the product being interacted with.
- `SubCategory`: The subcategory of the product.
- `Action`: The type of action performed by the user, such as viewing a product, reading reviews, making a purchase, adding a product to the cart, etc.
- `Quantity`: The number of products ordered in a transaction.
- `Rate`: The price of a single product unit.
- `Total Price`: The total order price, calculated as Quantity multiplied by Rate.

## Methodology
1. **Exploratory Data Analysis (EDA)**: Initial analysis to understand the data structure, distribution, and patterns.
2. **Feature Engineering**: Development of relevant features that capture user behavior and purchase patterns.
3. **RFM Analysis**: Segmentation of users based on Recency, Frequency, and Monetary values to understand customer value.
4. **Propensity Modeling**: Application of statistical models to predict the likelihood of a user making a purchase based on their behavior and characteristics.
