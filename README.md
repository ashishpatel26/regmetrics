# Regression Metrics
* Mean Absolute Error
* Mean Square Error
* Root Mean Square Error
* Root Mean Square Logarithmic Error
* Root Mean Square Logarithmic Error with negative value handle
* R2 Score
* Adjusted R2 Score
* Mean Absolute Percentage Error

```python
from regmetrics.metrics import *
y_true = [3, 0.5, 2, 7]
y_pred = [2.5, 0.0, 2, -8]


print("R2Score: ",r2(y_true, y_pred))
print("Adjusted_R2_Score:",adj_r2(y_true, y_pred))
print("RMSE:", rmse(y_true, y_pred))
print("MAE:",mae(y_true, y_pred))
print("RMSLE with Neg Value:", rmsle_with_negval(y_true, y_pred))
print("MSE:", mse(y_true, y_pred))
print("MAPE: ", mape(y_true, y_pred))
```
