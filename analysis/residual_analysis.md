# Residual Analysis

## Objective

The purpose of residual analysis is to evaluate how well the final **Multiple Regression Model** predicts monthly sales. Residuals help identify stores where the model performs exceptionally well and stores where additional business factors may be influencing sales beyond the variables included in the regression model.

---

# Residual Calculation

Predicted monthly sales were calculated using the final multiple regression equation.

Residuals were computed using the following formula:

```text
Residual = Actual Monthly Sales − Predicted Monthly Sales
```

### Interpretation of Residuals

* **Positive Residual:** Actual sales are higher than predicted (the model under-predicts sales).
* **Negative Residual:** Actual sales are lower than predicted (the model over-predicts sales).

---

# Stores with the Largest Positive Residuals

| Store ID |   Residual |
| -------- | ---------: |
| STR-1028 | 123,539.30 |
| STR-1026 | 114,468.20 |
| STR-1051 | 110,775.40 |
| STR-1073 |  98,971.54 |
| STR-1021 |  89,277.25 |

## Business Interpretation

These stores achieved significantly higher sales than predicted by the regression model.

Possible reasons include:

* Exceptional customer service
* Successful local marketing campaigns
* Strong customer loyalty
* Favorable seasonal demand
* Effective store management
* Other business factors not included in the regression model

These positive residuals suggest that additional variables may further improve the predictive performance of the model.

---

# Stores with the Largest Negative Residuals

| Store ID |    Residual |
| -------- | ----------: |
| STR-1017 | -162,777.10 |
| STR-1012 | -140,983.90 |
| STR-1023 | -122,167.80 |
| STR-1009 | -119,011.80 |
| STR-1077 | -111,236.40 |

## Business Interpretation

These stores generated lower sales than predicted by the model.

Possible explanations include:

* Operational inefficiencies
* Increased local competition
* Inventory shortages
* Staffing challenges
* Reduced customer demand
* External economic or regional factors not captured in the analysis

Further investigation of these stores may help identify opportunities for operational improvement.

---

# Overall Residual Assessment

The final **Multiple Regression Model** achieved an **R² (R Square) value of 0.8114**, indicating that approximately **81.14%** of the variation in monthly sales is explained by the variables included in the model.

Overall observations include:

* The model demonstrates strong predictive performance.
* Most stores are predicted with relatively small errors.
* Prediction errors are concentrated in a limited number of stores.
* There is no consistent pattern of systematic over-prediction or under-prediction.
* Remaining prediction errors likely result from business factors that were not included in the regression model.

These findings indicate that the model is reliable while still providing opportunities for improvement through the inclusion of additional explanatory variables.

---

# Conclusion

Residual analysis confirms that the **Multiple Regression Model** provides a strong overall fit for predicting monthly sales.

Although the model explains more than **81%** of the variation in sales, several stores exhibit unusually large positive or negative residuals. These stores should be investigated further to identify operational, regional, or market-specific factors that may improve future forecasting accuracy.

Overall, the model provides a dependable foundation for sales forecasting and supports informed business decision-making.

---

# Key Takeaways

* The Multiple Regression Model explains **81.14%** of the variation in monthly sales.
* Positive residuals indicate stores performing better than expected.
* Negative residuals indicate stores performing below expectations.
* Most prediction errors are limited to a small number of stores.
* Additional business variables could further improve forecasting accuracy.
* Residual analysis helps identify stores requiring further operational review.
