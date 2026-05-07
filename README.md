# Python_DataAnalysis_Shopping_Trends
# Statistical Analysis of Customer Shopping Trends

## Project Overview
This project presents a statistical and exploratory data analysis (EDA) of customer shopping behavior using Python. The study investigates customer demographics, purchasing behavior, customer satisfaction, seasonal trends, and payment preferences using descriptive statistics and visualization techniques.

The analysis was conducted on a dataset containing **3,900 customer shopping records** and aimed to generate business insights that can support data-driven decision-making in retail and e-commerce environments.

---

# Dataset Summary

| Statistic | Value |
|---|---|
| Total Observations | 3,900 |
| Total Variables | 19 |
| Missing Values | 0 |
| Duplicate Records | 0 |

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

# Descriptive Statistical Analysis

## Numerical Variable Summary

| Variable | Mean | Std Dev | Min | Median | Max |
|---|---|---|---|---|---|
| Age | 44.07 | 15.21 | 18 | 44 | 70 |
| Purchase Amount (USD) | 59.76 | 23.69 | 20 | 60 | 100 |
| Review Rating | 3.75 | 0.72 | 2.5 | 3.7 | 5.0 |
| Previous Purchases | 25.35 | 14.45 | 1 | 25 | 50 |

---

# Key Statistical Findings

## 1. Customer Demographics

### Age Distribution
- The average customer age was **44 years**.
- Customer ages ranged from **18 to 70 years**.
- The standard deviation of **15.21** indicates moderate age variability across customers.

### Interpretation
This suggests the customer base is broadly distributed across adult age groups, with middle-aged consumers forming a significant portion of the dataset.

---

# 2. Purchase Amount Analysis

## Average Purchase Amount by Category

| Category | Average Purchase Amount (USD) |
|---|---|
| Footwear | 60.26 |
| Clothing | 60.03 |
| Accessories | 59.84 |
| Outerwear | 57.17 |

### Key Insight
- **Footwear** generated the highest average purchase value.
- **Outerwear** recorded the lowest average spending among categories.

### Interpretation
Customers appear willing to spend more on footwear products, suggesting stronger perceived value or pricing power within this category.

---

# 3. Seasonal Spending Analysis

## Total Purchase Amount by Season

| Season | Total Purchase Amount (USD) |
|---|---|
| Fall | 60,018 |
| Spring | 58,679 |
| Winter | 58,607 |
| Summer | 55,777 |

### Key Insight
- **Fall** recorded the highest total sales.
- **Summer** produced the lowest total purchase amount.

### Interpretation
Seasonal demand significantly affects purchasing activity, indicating opportunities for seasonal inventory and marketing optimization.

---

# 4. Customer Satisfaction Analysis

## Average Review Rating by Season

| Season | Mean Review Rating |
|---|---|
| Spring | 3.79 |
| Winter | 3.75 |
| Fall | 3.73 |
| Summer | 3.73 |

### Key Insight
- Customer satisfaction remained relatively stable across all seasons.
- Spring recorded the highest average review rating.

### Interpretation
The consistency in ratings suggests relatively stable customer experiences throughout the year.

---

# 5. Discount Impact Analysis

## Mean Review Rating by Discount Status

| Discount Applied | Mean Review Rating |
|---|---|
| No | 3.758 |
| Yes | 3.740 |

### Key Insight
- Discounted purchases showed only a marginal difference in review ratings.

### Interpretation
Discount strategies do not appear to negatively impact customer satisfaction.

---

# 6. Payment Method Analysis

## Preferred Payment Methods

| Payment Method | Frequency |
|---|---|
| PayPal | 677 |
| Credit Card | 671 |
| Cash | 670 |
| Debit Card | 636 |
| Venmo | 634 |
| Bank Transfer | 612 |

### Total Purchase Amount by Payment Method

| Payment Method | Total Purchase Amount (USD) |
|---|---|
| Credit Card | 42,567 |
| Venmo | 39,991 |
| Cash | 38,833 |
| PayPal | 37,449 |
| Bank Transfer | 37,123 |
| Debit Card | 37,118 |

### Interpretation
Digital payment methods dominate customer transactions, with credit cards generating the highest transaction value.

---

# 7. Product Preference Analysis

## Most Popular Colors

| Color | Frequency |
|---|---|
| Olive | 177 |
| Yellow | 174 |
| Silver | 173 |
| Teal | 172 |
| Green | 169 |

### Interpretation
Neutral and earthy colors appear highly preferred among customers.

---

# 8. Purchase Frequency Analysis

## Median Previous Purchases by Purchase Frequency

| Frequency of Purchases | Median Previous Purchases |
|---|---|
| Quarterly | 28 |
| Weekly | 26 |
| Fortnightly | 26 |
| Monthly | 25 |
| Annually | 24 |

### Key Insight
Customers purchasing more frequently generally showed higher previous purchase counts.

### Interpretation
Repeat purchasing behavior indicates strong customer retention potential.

---

# 9. Size-Based Spending Analysis

## Average Purchase Amount by Size

| Size | Average Purchase Amount (USD) |
|---|---|
| Small (S) | 61.04 |
| Extra Large (XL) | 60.09 |
| Medium (M) | 59.92 |
| Large (L) | 58.56 |

### Interpretation
Customers purchasing smaller sizes demonstrated slightly higher average spending.

---

# Statistical Conclusions

The analysis revealed that:

- Customer spending behavior varies across product categories and seasons.
- Payment preferences are strongly concentrated around digital payment platforms.
- Customer satisfaction remained consistently positive across all conditions analyzed.
- Repeat purchasing behavior indicates strong retention opportunities.
- Seasonal effects influence both transaction volume and customer engagement.

---

# Business Recommendations

## 1. Focus on High-Performing Categories
Increase marketing and inventory investment in:
- Footwear
- Clothing

These categories generated the highest average spending.

---

## 2. Implement Seasonal Marketing Strategies
Since Fall generated the highest total sales:
- Increase promotions before Fall season
- Adjust inventory planning around seasonal demand trends

---

## 3. Strengthen Customer Retention Programs
Frequent buyers demonstrated stronger purchasing behavior. Businesses should:
- Develop loyalty programs
- Introduce customer rewards systems
- Offer personalized recommendations

---

## 4. Optimize Digital Payment Experience
Because digital payment methods dominated transactions:
- Improve payment convenience
- Prioritize secure online payment systems
- Support preferred digital payment channels

---

## 5. Use Customer Feedback Strategically
Maintain continuous review monitoring to:
- Detect product/service issues
- Improve customer satisfaction
- Enhance product offerings

---

# Future Improvements

Potential extensions of this project include:

- Predictive analytics for customer spending
- Customer segmentation using clustering algorithms
- Time series forecasting
- Machine learning recommendation systems
- Interactive Power BI dashboards

---

# Author

## Fortune Maake

Aspiring Data Analyst and Data Scientist with interests in:
- Statistical Analysis
- Business Intelligence
- Financial Analytics
- Machine Learning
- Data Visualization
- Customer Analytics
