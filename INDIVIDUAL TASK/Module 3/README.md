## Correlation Exploration
## Daily Life Case Study: Hours vs Scores & Screen Time vs Productivity
## Introduction
Correlation measures the relationship between two variables. 
It tells us whether variables move together.
Represented by correlation coefficient (r).
Value of r lies between –1 and +1

## Types of Correlation
- Positive Correlation (+r)
When one variable increases, the other also increases.
Example: Study hours ↑ → Scores ↑
- Negative Correlation (–r)
When one variable increases, the other decreases.
Example: Screen time ↑ → Productivity ↓
- Zero Correlation (r ≈ 0)
No relationship between variables.

## Example:
## Case 1:
| Student | Study Hours (X) | Exam Score (Y) |
| ------- | --------------- | -------------- |
| A       | 2               | 40             |
| B       | 3               | 50             |
| C       | 4               | 60             |
| D       | 5               | 70             |
| E       | 6               | 80             |

## Karl Pearson’s Correlation Coefficient:
$$
r = \frac{n\sum XY - (\sum X)(\sum Y)}
{\sqrt{[n\sum X^2 - (\sum X)^2][n\sum Y^2 - (\sum Y)^2]}}
$$

    
## Case 2:
| Person | Screen Time (hrs) (X) | Productivity Score (Y) |
| ------ | --------------------- | ---------------------- |
| A      | 2                     | 90                     |
| B      | 3                     | 80                     |
| C      | 4                     | 70                     |
| D      | 5                     | 60                     |
| E      | 6                     | 50                     |

## Pearson’s Correlation (Deviation Method):
$$
x = X - \bar{X}
$$

$$
y = Y - \bar{Y}
$$

$$
r = \frac{\sum (X - \bar{X})(Y - \bar{Y})}
{\sqrt{\sum (X - \bar{X})^2 \sum (Y - \bar{Y})^2}}
$$



## Steps to Calculate Correlation:
- Collect paired data (X and Y).
- Create a table with columns: X, Y, X², Y², XY.
- Calculate ΣX, ΣY, ΣX², ΣY², ΣXY.
- Substitute values into formula.
- Interpret result.

## Interpretation of r Value
| Value of r    | Type of Correlation | Interpretation                            |
| ------------- | ------------------- | ----------------------------------------- |
| +1            | Perfect Positive    | Both variables increase together exactly. |
| +0.8 to +0.99 | Strong Positive     | Very strong upward relationship.          |
| +0.5 to +0.79 | Moderate Positive   | Clear positive relationship.              |
| +0.1 to +0.49 | Weak Positive       | Slight positive relationship.             |
| 0             | No Correlation      | No relationship between variables.        |
| –0.1 to –0.49 |                     |                                           |


## Graphical Representation
1. Use scatter diagram.
2. If points move upward → Positive correlation.
3. If points move downward → Negative correlation.
4. If scattered randomly → No correlation.

## Importance of Correlation
- Helps in prediction.
- Useful in research and data analysis.
- Helps understand relationships in business, education, health.
- Used in economics and statistics.

## Advantages of Correlation
- Simple to calculate
- Helps in prediction
- Useful in trend analysis
- Basis for regression analysis
- Helps in research studies

## Real-Life Applications of Correlation
1. In Education
- Study time vs performance
- Attendance vs grades

2. In Business
- Advertising cost vs sales
- Price vs demand

3. In Health
- Exercise vs cholesterol level
- Sleep hours vs concentration

4. In Economics
- Income vs expenditure
- Inflation vs purchasing power

## Limitations of Correlation
- Correlation does not imply causation.
- A high correlation may be coincidental.
- Affected by extreme values (outliers).


## Conclusion
“The calculated correlation coefficient shows a strong positive relationship between study hours and exam scores. This means that students who study more tend to score higher marks. However, correlation does not imply causation, and other factors such as intelligence, teaching quality, and environment may also affect performance.”
