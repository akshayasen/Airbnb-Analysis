# Airbnb-Analysis

Problem Statement

The pricing and availability of Airbnb listings vary based on multiple factors such as room type, accommodation size, and cancellation policies. Understanding these patterns can help optimize pricing strategies, improve customer satisfaction, and maximize revenue.

Objective

The main goal of this analysis is to explore how different factors like room type, cleaning fees, and cancellation policies impact the pricing of Airbnb listings. By analyzing patterns in the dataset, we aim to derive insights that can help hosts and potential customers make informed decisions.

Dataset

The dataset contains Airbnb listing details, including features such as:

log_price: The logarithm of the listing price

room_type: Type of room (Entire home/apt, Private room, Shared room)

accommodates: Number of people the listing can accommodate

cancellation_policy: Type of cancellation policy (Flexible, Moderate, Strict)

cleaning_fee: Whether a cleaning fee is charged (True/False)

Data Analysis

Univariate Analysis

The log_price distribution is right-skewed, indicating that most listings have lower prices.

Room type distribution shows that most listings are Entire home/apartments.

The standard deviation of log_price suggests moderate variation in pricing across listings.

Bivariate Analysis

The correlation between accommodates and log_price is 0.56, indicating a moderate positive relationship.

Box plots revealed that Entire home/apartments have higher prices than private or shared rooms.

Cross-tabulation between room_type and cancellation_policy showed that stricter policies are more common in Entire home/apartments.

Key Insights

Entire home/apartments tend to have the highest prices, while shared rooms are the cheapest.

Larger accommodations generally lead to higher prices, suggesting that hosts can optimize revenue by accommodating more guests.

Stricter cancellation policies are more common for high-priced listings, likely to protect host revenue.

Conclusion

This analysis provided a clear understanding of how pricing is influenced by different factors in Airbnb listings. Insights from the study can help hosts optimize their pricing strategies and set appropriate cancellation policies. Future work can explore additional factors like location and guest reviews for deeper insights.
