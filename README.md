# anushka_bitsom_ba_2511785_part3_regression_insights
# Part 3: Regression-Based Business Insights & Model Interpretation

## Business Problem Summary

This project analyzes the factors associated with monthly sales across retail stores using regression analysis. The objective is to identify the key business drivers of sales and provide data-driven recommendations to help leadership make informed decisions regarding marketing, inventory management, and regional performance.

---

# Dataset Description

The dataset contains information for 320 retail stores with variables related to sales, customer activity, inventory, discounts, and regional information.

## Dependent Variable

* Monthly Sales

## Independent Variables

* Marketing Spend
* Footfall
* Inventory Availability Percentage
* Average Discount Percentage
* Customer Rating
* Competitor Distance (km)
* Region
* Store Type

---

# Dataset Understanding

## Numerical Variables

* Monthly Sales
* Marketing Spend
* Footfall
* Inventory Availability Percentage
* Average Discount Percentage
* Customer Rating
* Competitor Distance (km)

## Categorical Variables

* Region
* Store Type

## Data Cleaning Performed

* Checked for missing values.
* Replaced missing values in numerical columns using the column average.
* Verified that no duplicate records were present.
* Prepared categorical variables for regression analysis using dummy variables.

## Variables Not Used Directly

Categorical variables cannot be used directly in regression. Therefore, Region was converted into dummy variables before building the regression model.

---

# Regression Approach

The analysis was performed using Microsoft Excel with the Data Analysis ToolPak.

The following steps were completed:

* Data cleaning
* Data preparation
* Dummy variable creation
* Simple Linear Regression
* Multiple Linear Regression
* Model comparison
* Predicted sales calculation
* Residual analysis
* Business interpretation and recommendations

---

# Dummy Variable Approach

The categorical variable Region was converted into dummy variables.

The following dummy variables were created:

* East Dummy
* North Dummy
* West Dummy

The South region was selected as the reference category and excluded from the regression model to avoid multicollinearity (dummy variable trap).

---

# Model Comparison Summary

| Model                               | R Square | Summary                                                                                                            |
| ----------------------------------- | :------: | ------------------------------------------------------------------------------------------------------------------ |
| Simple Regression (Marketing Spend) |  0.1672  | Marketing spend has a positive relationship with monthly sales but explains only a small portion of the variation. |
| Simple Regression (Footfall)        |  0.7363  | Footfall is a strong predictor of monthly sales and explains a significant portion of sales variation.             |
| Multiple Regression                 |  0.8114  | Best-performing model with the highest explanatory power using multiple business variables simultaneously.         |

---

# Final Model Selected

The Multiple Regression Model was selected because it achieved the highest R Square (0.8114) and explained approximately 81.14% of the variation in monthly sales.

Important variables in the final model include:

* Marketing Spend
* Footfall
* Inventory Availability Percentage
* East Dummy

The North and West dummy variables were not statistically significant.

---

# Business Recommendation

Based on the regression analysis, the leadership team should:

* Increase customer footfall through effective marketing campaigns.
* Continue investing in marketing activities with measurable returns.
* Maintain high inventory availability to minimize lost sales.
* Investigate lower-performing stores in the East region.
* Use regression findings as a decision-support tool while considering operational and market factors.

---

# Assumptions and Limitations

* Regression analysis shows association but does not prove causation.
* Some business factors affecting sales were not included in the dataset.
* Prediction accuracy depends on the quality of the available data.
* External factors such as seasonality, competition, and customer preferences may also influence sales.

---

# Required Folder Structure

```text
part3_regression_insights/
├── data/
│   └── business_regression_data.xlsx
├── analysis/
│   ├── regression_workbook.xlsx
│   ├── model_comparison.md
│   └── residual_analysis.md
├── outputs/
│   ├── regression_summary.xlsx
│   ├── final_recommendation.md
│   └── model_equations.md
├── screenshots/
│   ├── simple_regression_output.png
│   ├── multiple_regression_output.png
│   ├── residuals_preview.png
│   └── model_comparison_preview.png
└── README.md
```

---

# Screenshots Included

The repository contains the following screenshots as evidence of the completed regression analysis:

* `simple_regression_output.png`
* `multiple_regression_output.png`
* `residuals_preview.png`
* `model_comparison_preview.png`

---

# Tools Used

* Microsoft Excel
* Excel Data Analysis ToolPak
* Simple Linear Regression
* Multiple Linear Regression
* Dummy Variable Encoding
* Residual Analysis

---

# Conclusion

The regression analysis demonstrates that customer footfall, marketing spend, and inventory availability are the strongest factors associated with monthly sales. The multiple regression model provides the best predictive performance and serves as the final model for business decision-making. While regression offers valuable insights into relationships between variables, business decisions should also consider operational knowledge and external factors beyond the available data.
