# Model Equations

## Objective

The purpose of this document is to present the regression equations developed during the analysis, explain the meaning of each coefficient, describe the dummy variable approach, and justify the selection of the final model.

---

# Simple Regression Model 1

## Dependent Variable

* Monthly Sales

## Independent Variable

* Marketing Spend

## Regression Equation

```text
Monthly Sales = 409,998.81 + 1.30 × Marketing Spend
```

## Interpretation

* **Intercept (409,998.81):** Estimated monthly sales when marketing spend is zero.
* **Marketing Spend Coefficient (1.30):** Every additional ₹1 spent on marketing is associated with an increase of approximately ₹1.30 in monthly sales.
* **R Square:** 0.1672

## Business Meaning

Marketing spend has a positive and statistically significant relationship with monthly sales. However, it explains only a limited portion of the variation in sales and should not be used as the only predictor.

---

# Simple Regression Model 2

## Dependent Variable

* Monthly Sales

## Independent Variable

* Footfall

## Regression Equation

```text
Monthly Sales = 446,410.58 + 35.68 × Footfall
```

## Interpretation

* **Intercept (446,410.58):** Estimated monthly sales when customer footfall is zero.
* **Footfall Coefficient (35.68):** Every additional customer visiting the store is associated with an increase of approximately ₹35.68 in monthly sales.
* **R Square:** 0.7363

## Business Meaning

Customer footfall is a strong predictor of monthly sales and explains a large proportion of the variation in sales.

---

# Multiple Regression Model

## Dependent Variable

* Monthly Sales

## Independent Variables

* Marketing Spend
* Footfall
* Inventory Availability Percentage
* East Dummy
* North Dummy
* West Dummy

## Regression Equation

```text
Monthly Sales = 153,400.80 + (1.1859 × Marketing Spend) + (33.8704 × Footfall) + (2818.2068 × Inventory Availability %) − (21,940.49 × East Dummy) − (11,393.11 × North Dummy) − (4,449.12 × West Dummy)
```

---

# Explanation of Coefficients

| Variable               | Business Interpretation                                                                                                     |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| Marketing Spend        | Higher marketing expenditure is associated with increased monthly sales.                                                    |
| Footfall               | Stores receiving more customer visits generally achieve higher sales.                                                       |
| Inventory Availability | Better inventory availability is associated with improved sales performance.                                                |
| East Dummy             | East region stores tend to have lower monthly sales compared to the reference region after controlling for other variables. |
| North Dummy            | Difference from the reference region is not statistically significant.                                                      |
| West Dummy             | Difference from the reference region is not statistically significant.                                                      |

---

# Dummy Variable Approach

The Region variable is categorical and cannot be used directly in regression analysis. Therefore, dummy variables were created.

The following dummy variables were included:

* East Dummy
* North Dummy
* West Dummy

The South region was used as the reference category and was intentionally excluded from the regression model to avoid the dummy variable trap (perfect multicollinearity).

Each dummy variable takes the following values:

* **1 =** Store belongs to that region.
* **0 =** Store does not belong to that region.

---

# Final Model Selection

The Multiple Regression Model was selected as the final model because it provides the highest explanatory power (R Square = 0.8114) and includes multiple important business variables simultaneously.

Compared with the simple regression models, the multiple regression model offers better prediction accuracy and provides more comprehensive insights for business decision-making.
