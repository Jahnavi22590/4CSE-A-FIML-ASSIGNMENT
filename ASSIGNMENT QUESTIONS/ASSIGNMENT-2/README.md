##  Domain: **Student IQ Scores in a University**

#  1. Normal Distribution 

A **Normal Distribution** (also called Gaussian Distribution) is a continuous probability distribution that is:

* 1. Bell-shaped
* 2. Symmetrical around the mean
* 3. Mean = Median = Mode
* 4. Defined by two parameters:

1. Mean (μ) → Center of distribution
2. Standard Deviation (σ)→ Spread of data

The total area under the curve = **1 (or 100%)**


# 2. Assumed Data for Our Domain

Let us assume:

* Mean IQ (μ) = **100**
* Standard Deviation (σ) = **15**

This is a standard assumption used in psychological testing.



#  3. Empirical Rule (68–95–99.7 Rule)

The **Empirical Rule** applies only to **normal distributions**.

It states:

| Range  | Percentage of Data | IQ Range  |
| ------ | ------------------ | --------- |
| μ ± 1σ | 68%                | 85 to 115 |
| μ ± 2σ | 95%                | 70 to 130 |
| μ ± 3σ | 99.7%              | 55 to 145 |

---

#  4. Interpretation in Our Domain

### 68% of Students (Average Range)

* IQ between **85 and 115**
* Most students fall here
* Considered “Average intelligence”



### 95% of Students

* IQ between **70 and 130**
* Includes below-average and above-average students
* Only 5% lie outside this range



###  99.7% of Students

* IQ between **55 and 145**
* Almost all students fall within this range
* Only 0.3% are extreme outliers



#  5. Distribution Structure 

From left to right:

```
55     70     85     100     115     130     145
-3σ    -2σ    -1σ     μ      +1σ     +2σ     +3σ
```

Breakdown of percentages in each section:

* 34% between μ and +1σ
* 34% between μ and -1σ
* 13.5% between 1σ and 2σ (each side)
* 2.35% between 2σ and 3σ (each side)
* 0.15% beyond 3σ (each tail)



#  6. Mathematical Formula of Normal Distribution

Probability Density Function (PDF):

## Normal Distribution – Probability Density Function (PDF)

The probability density function of a normal distribution is:

$$
f(x) = \frac{1}{\sigma \sqrt{2\pi}} \, e^{-\frac{(x - \mu)^2}{2\sigma^2}}
$$

Where:

- $\mu$ = Mean  
- $\sigma$ = Standard Deviation  
- $x$ = Random variable  
- $\pi$ = 3.1416  
- $e$ = 2.718



#  7. Important Properties

1. Symmetrical
2. Bell-shaped
3. Mean = Median = Mode
4. Total probability = 1
5. Tails approach x-axis but never touch



#  8. Z-Score Concept

The Z-score formula is:
## $Z = \frac{X - \mu}{\sigma}$
  

Example:

If IQ = 130:
$$
Z = \frac{X - \mu}{\sigma}
$$

$$
Z = \frac{130 - 100}{15}
$$

$$
Z = \frac{30}{15}
$$

$$
Z = 2
$$

Meaning:
The student is **2 standard deviations above the mean**.



#  9. Real-Life Applications in This Domain

* Identifying gifted students
* Detecting learning difficulties
* Scholarship eligibility
* Standardized testing analysis
* Psychological research



#  10. Why IQ Follows Normal Distribution?

Because:

* IQ is influenced by many small independent factors (genetics, environment, education)
* According to the **Central Limit Theorem**, such variables tend to form a normal distribution



#  11. Outliers in This Domain

* IQ < 55 → Extremely low (very rare)
* IQ > 145 → Extremely high (very rare)

Probability of such extreme values ≈ 0.3%



#  12. Conclusion

For a **perfect normal distribution**:

✔ 68% data lies within 1σ
✔ 95% data lies within 2σ
✔ 99.7% data lies within 3σ



