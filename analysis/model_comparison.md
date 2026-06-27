# Model Comparison

## Objective

The objective of this analysis was to compare different regression models to identify which factors are most strongly associated with monthly sales and determine the most useful model for business decision-making.

---

## Model Comparison Table

| Model               | Dependent Variable | Independent Variable(s)                                                                    | R Square | Significant Variables                                             | Business Usefulness                                                                                                   | Limitations                                                                                                                            |
| ------------------- | ------------------ | ------------------------------------------------------------------------------------------ | :------: | ----------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| Simple Regression 1 | monthly_sales      | marketing_spend                                                                            |  0.1672  | marketing_spend                                                   | Shows that higher marketing spend is positively associated with higher monthly sales.                                 | Explains only a small portion of the variation in sales.                                                                               |
| Simple Regression 2 | monthly_sales      | footfall                                                                                   |  0.7363  | footfall                                                          | Demonstrates that customer footfall is a strong predictor of monthly sales.                                           | Considers only one factor and ignores other business variables.                                                                        |
| Multiple Regression | monthly_sales      | marketing_spend, footfall, inventory_availability_pct, East_Dummy, North_Dummy, West_Dummy |  0.8114  | marketing_spend, footfall, inventory_availability_pct, East_Dummy | Provides the most comprehensive explanation of monthly sales by considering multiple business factors simultaneously. | North and West dummy variables are not statistically significant. Regression identifies associations and does not establish causation. |

---

## Comparison of Models

### Simple Regression Model 1 – Marketing Spend

This model evaluates the relationship between marketing spend and monthly sales. The model produced an R Square value of 0.1672, indicating that marketing spend alone explains approximately 16.72% of the variation in monthly sales. Although marketing spend has a positive and statistically significant relationship with sales, additional variables are required to improve prediction accuracy.

### Simple Regression Model 2 – Footfall

This model uses footfall as the only predictor of monthly sales. It achieved an R Square of 0.7363, meaning that approximately 73.63% of the variation in monthly sales is explained by customer footfall. This makes footfall a much stronger individual predictor than marketing spend.

### Multiple Regression Model

The multiple regression model includes marketing spend, footfall, inventory availability percentage, and regional dummy variables. It achieved the highest R Square value of 0.8114, explaining approximately 81.14% of the variation in monthly sales.

Marketing spend, footfall, inventory availability percentage, and the East regional dummy variable were statistically significant predictors. The North and West dummy variables were not statistically significant, suggesting that their differences from the reference region were not meaningful after accounting for the other variables.

---

## Final Model Selection

The Multiple Regression Model was selected as the final model because it provides the highest explanatory power and incorporates several important business variables simultaneously. Compared with the simple regression models, it offers more reliable insights for business planning and decision-making.

---

## Business Conclusion

The analysis indicates that customer footfall, marketing spend, and inventory availability are the strongest factors associated with monthly sales. The multiple regression model provides the best balance between prediction accuracy and business interpretability and is therefore recommended for supporting retail management decisions.
