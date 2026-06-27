# Residual Analysis

## Objective

The purpose of residual analysis is to evaluate how well the final multiple regression model predicts monthly sales. Residuals help identify stores where the model performs exceptionally well or where additional business factors may be influencing sales.

---

## Residual Calculation

Predicted monthly sales were calculated using the final multiple regression equation. Residuals were computed using the following formula:

```text
Residual = Actual Monthly Sales − Predicted Monthly Sales
```

* **Positive residual:** Actual sales are higher than predicted (under-prediction by the model).
* **Negative residual:** Actual sales are lower than predicted (over-prediction by the model).

---

## Stores with the Largest Positive Residuals

| Store ID |   Residual |
| -------- | ---------: |
| STR-1028 | 123,539.30 |
| STR-1026 | 114,468.20 |
| STR-1051 | 110,775.40 |
| STR-1073 |  98,971.54 |
| STR-1021 |  89,277.25 |

### Business Interpretation

These stores achieved significantly higher sales than predicted by the regression model. This suggests that additional factors not included in the analysis—such as exceptional customer service, successful local promotions, strong brand loyalty, favorable seasonal demand, or effective store management—may have positively influenced sales performance.

---

## Stores with the Largest Negative Residuals

| Store ID |    Residual |
| -------- | ----------: |
| STR-1017 | -162,777.10 |
| STR-1012 | -140,983.90 |
| STR-1023 | -122,167.80 |
| STR-1009 | -119,011.80 |
| STR-1077 | -111,236.40 |

### Business Interpretation

These stores recorded lower sales than predicted by the model. Possible reasons include operational inefficiencies, increased local competition, inventory shortages, staffing issues, reduced customer demand, or other external factors that were not included in the regression analysis.

---

# Overall Residual Assessment

The final multiple regression model achieved an R Square of 0.8114, indicating that it explains approximately 81.14% of the variation in monthly sales. Although the model performs well overall, the residual analysis shows that certain stores still experience prediction errors due to factors beyond the variables included in the model.

The model does not consistently over-predict or under-predict all stores. Instead, the prediction errors are concentrated in a relatively small number of stores, suggesting that the model is reliable while still leaving room for improvement through the inclusion of additional business variables.

---

# Conclusion

Residual analysis confirms that the multiple regression model provides a strong overall fit for predicting monthly sales. However, leadership should investigate stores with unusually large positive or negative residuals to identify additional operational or market factors that may improve future forecasting accuracy and business decision-making.
