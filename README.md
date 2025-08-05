#  Airbnb-Analysis

##   Problem Statement

The pricing and availability of Airbnb listings vary based on multiple factors such as room type, accommodation size, and cancellation policies. Understanding these patterns can help optimize pricing strategies, improve customer satisfaction, and maximize revenue.

---

##  Objective

The main goal of this analysis is to explore how different factors—like room type, cleaning fees, and cancellation policies—impact the pricing of Airbnb listings. By analyzing patterns in the dataset, we aim to derive insights that help both hosts and potential customers make informed decisions.

---

##  Dataset Description

The dataset contains various details of Airbnb listings, including the following key features:

- `log_price`: The natural logarithm of the listing price  
- `room_type`: Type of room (`Entire home/apt`, `Private room`, `Shared room`)  
- `accommodates`: Number of people the listing can accommodate  
- `cancellation_policy`: Type of cancellation policy (`Flexible`, `Moderate`, `Strict`)  
- `cleaning_fee`: Whether a cleaning fee is charged (`True`/`False`)  

---

##  Data Analysis

###  Univariate Analysis

- The `log_price` distribution is **right-skewed**, indicating most listings have **lower prices**.
- Most listings are categorized under **Entire home/apartments**.
- The **standard deviation** of `log_price` shows **moderate variation** in pricing across listings.

###  Bivariate Analysis

- The **correlation** between `accommodates` and `log_price` is **0.56**, indicating a **moderate positive relationship**.
- **Box plots** reveal that **Entire home/apartments** have significantly **higher prices** than Private or Shared rooms.
- **Cross-tabulation** between `room_type` and `cancellation_policy` shows **stricter policies** are more common in **Entire home/apartments**.

---

##  Key Insights

- **Entire home/apartments** tend to have the **highest prices**, while **shared rooms** are the **cheapest**.
- **Larger accommodations** generally lead to **higher prices**, suggesting hosts can optimize revenue by **hosting more guests**.
- **Stricter cancellation policies** are more common for **high-priced listings**, likely used to **protect host revenue**.

---

##  Conclusion

This analysis provides a clear understanding of how pricing is influenced by various factors in Airbnb listings:

- Helps hosts **optimize pricing** strategies.
- Supports decision-making for **appropriate cancellation policies**.
- Reveals actionable insights to improve **customer satisfaction** and **profitability**.

**Future Scope**: The study can be extended to include **location**, **guest reviews**, and **seasonality trends** to further enhance the pricing strategy and overall customer experience.

---

## 🛠 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- CSV for data storage

    └── price_distribution.png     # Optional images for visuals (add screenshots here)
