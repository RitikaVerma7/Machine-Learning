# Skincare Recommendation System Projects

## Price Prediction for Products
Develop a regression model to accurately predict the price of products listed on our e-commerce platform based on various product features.

- **Dataset:** `Product_info.csv`
- **Main Features:** `Brand ID`, `Variation Value` (Product Quantity), `Primary Category`, `brand_id`
- **Model/Technique:** A regression technique will be utilized, given the continuous nature of the target variable (Price). We will explore multiple regression algorithms, starting with Linear Regression for a baseline, and potentially more complex models like Random Forest and Gradient Boosting for increased accuracy.
- **Rationale:** Regression analysis is best suited for predicting prices, a continuous variable, based on the product's key features. This will allow us to understand how different features contribute to the final price of a product.

## Recommendation Flag Prediction based on Customer Reviews
Create a machine learning model to predict product recommendations by customers.

- **Dataset:** `reviews.csv`
- **Main Features:** `total_neg_feedback_count`, `total_pos_feedback_count`, `skin_tone`, `eye_color`, `skin_type`, `hair_color`
- **Model/Technique:** Binary Classification. We'll utilize a classification algorithm (e.g., Logistic Regression, Random Forest, or Gradient Boosting) to predict the binary outcome of `is_recommended` based on both quantitative feedback metrics and derived features from sentiment analysis.
- **Rationale:** The goal is to personalize product recommendations to customers based on their traits and preferences, enhancing the shopping experience.

