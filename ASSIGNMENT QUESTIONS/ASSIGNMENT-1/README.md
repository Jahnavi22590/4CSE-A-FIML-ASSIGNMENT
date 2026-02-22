## Variance and Bias (Overfitting & Underfitting)
### 1. What is Bias?
* **Bias** is the error due to overly simple assumptions in the model.
* High bias → Model is too simple → **Underfitting**
* Low bias → Model fits training data well

### 2. What is Variance?
* **Variance** is the error due to too much complexity in the model.
* High variance → Model changes a lot with new data → **Overfitting**
* Low variance → Model is stable across different datasets

## Best Fit Model:
For the **best fit model**, we need:
* LOW BIAS AND LOW VARIANCE 

This gives:

1. Good training accuracy
2. Good test accuracy
3. Proper generalization

## Diagram:

```
                    MODEL COMPLEXITY
Low  ------------------------------------------------------> High

      Underfitting             Best Fit                Overfitting
      (High Bias,             (Low Bias,              (Low Bias,
       Low Variance)           Low Variance)           High Variance)

Training Error:   High  ↓↓↓  Medium  ↓   Very Low
Testing Error:    High  ↓↓↓  Low     ↓   High
```

##  Bias–Variance Tradeoff Curve 

```
Error
^
| \                Test Error
|  \              /\
|   \            /  \
|    \          /    \
|     \        /      \
|      \______/        \______
|       \
|        \
|         \
|          \
|           \ Training Error
|
+------------------------------------> Model Complexity
     High Bias        Optimal       High Variance
   (Underfitting)     Point        (Overfitting)
```


##  Summary Table:

| Model Type   | Bias | Variance | Problem     |
| ------------ | ---- | -------- | ----------- |
| Underfitting | High | Low      | Too simple  |
| Best Fit     | Low  | Low      | Ideal model |
| Overfitting  | Low  | High     | Too complex |

---

## For **best fit model** →
✔ **Low Bias and Low Variance**

