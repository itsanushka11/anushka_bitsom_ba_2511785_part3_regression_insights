# Model Comparison

## Objective

The objective of this analysis was to compare different regression models to determine which factors are most strongly associated with **monthly sales** and identify the most suitable model for business decision-making.

---

# Model Comparison Summary

| Model | Dependent Variable | Independent Variable(s) | R Square | Significant Variables | Business Usefulness | Limitations |
|:------|:-------------------|:------------------------|:-------:|:----------------------|:--------------------|:------------|
| **Simple Regression 1** | Monthly Sales | Marketing Spend | **0.1672** | Marketing Spend | Demonstrates that increased marketing spend is positively associated with higher monthly sales. | Explains only a small portion of the variation in sales. |
| **Simple Regression 2** | Monthly Sales | Footfall | **0.7363** | Footfall | Shows that customer footfall is a strong predictor of monthly sales. | Considers only one predictor and ignores other important business factors. |
| **Multiple Regression** | Monthly Sales | Marketing Spend, Footfall, Inventory Availability %, East Dummy, North Dummy, West Dummy | **0.8114** | Marketing Spend, Footfall, Inventory Availability %, East Dummy | Provides the most comprehensive explanation of monthly sales by considering multiple business variables simultaneously. | North and West regional dummy variables are not statistically significant. Regression identifies associations rather than causation. |
---

# Model Evaluation

## 1. Simple Regression Model – Marketing Spend

This model evaluates the relationship between **marketing spend** and **monthly sales**.

### Results

- **R Square:** 0.1672
- Marketing spend is statistically significant.
- Approximately **16.72%** of the variation in monthly sales is explained by marketing spend.

### Interpretation

Although marketing investment has a positive relationship with monthly sales, it explains only a limited proportion of sales variation. Other business factors clearly influence sales performance and should be included for better prediction.

---

## 2. Simple Regression Model – Footfall

This model evaluates **customer footfall** as the sole predictor of monthly sales.

### Results

- **R Square:** 0.7363
- Footfall is statistically significant.
- Approximately **73.63%** of the variation in monthly sales is explained by customer footfall.

### Interpretation

Customer footfall is a much stronger individual predictor than marketing spend. Stores receiving higher customer traffic generally generate higher sales.

---

## 3. Multiple Regression Model

The multiple regression model includes the following predictors:

- Marketing Spend
- Footfall
- Inventory Availability (%)
- East Region Dummy
- North Region Dummy
- West Region Dummy

### Results

- **R Square:** 0.8114
- Significant Variables:
  - Marketing Spend
  - Footfall
  - Inventory Availability (%)
  - East Region Dummy

### Interpretation

The multiple regression model explains approximately **81.14%** of the variation in monthly sales, making it the strongest-performing model.

The analysis indicates that:

- Higher marketing expenditure contributes positively to sales.
- Increased customer footfall significantly improves sales performance.
- Better inventory availability is associated with higher monthly sales.
- Stores located in the East region perform differently from the reference region after controlling for other variables.

The North and West regional dummy variables are **not statistically significant**, suggesting their impact is not meaningful once other predictors are included.

---

# Final Model Selection

The **Multiple Regression Model** was selected as the preferred model because it provides:

- The highest explanatory power (**R² = 0.8114**)
- Better prediction accuracy
- Simultaneous evaluation of multiple business factors
- More reliable insights for strategic planning and decision-making

Compared with the simple regression models, it captures a substantially larger proportion of the variation in monthly sales.

---

# Business Conclusion

The regression analysis indicates that the strongest factors associated with monthly sales are:

- Customer Footfall
- Marketing Spend
- Inventory Availability

Among all evaluated models, the **Multiple Regression Model** delivers the best balance between predictive performance and business interpretability.

Based on these findings, the multiple regression model is recommended for forecasting monthly sales and supporting retail management decisions related to marketing investment, inventory planning, and store performance evaluation.

---

# Key Takeaways

- Marketing spend positively influences monthly sales.
- Customer footfall is the strongest individual predictor of sales.
- Inventory availability significantly contributes to improved sales performance.
- The East regional effect is statistically significant.
- The Multiple Regression Model provides the most accurate and reliable predictions.
- Regression analysis identifies statistical relationships but does **not** establish causation.