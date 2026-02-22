## Domain: **Online Food Delivery Platform** (like Zomato or Swiggy)
![Screenshot_22-2-2026_154232_www bing com](https://github.com/user-attachments/assets/0e5d55b2-836c-4f32-b919-0edd0c28f8a5)


# 1️. Business Understanding (CRISP-DM – Phase 1)

Business Understanding is the **first and most important phase** in any Data Science / Machine Learning project.

It focuses on:

* Understanding the **business problem**
* Defining **objectives**
* Identifying **constraints**
* Determining **success criteria**
* Translating business goals into **data science goals**

Without proper business understanding, even a technically perfect model can fail.



#  2. Business Background

An online food delivery platform connects:

* Customers
* Restaurants
* Delivery partners

The company earns revenue through:

* Commission from restaurants
* Delivery charges
* Advertisements
* Subscription models (like premium memberships)

### Current Business Challenges

1. Late deliveries
2. Customer churn (users uninstalling the app)
3. Low order frequency
4. High delivery costs
5. Poor restaurant ratings
6. Inefficient delivery partner allocation



# 3. Define the Business Problem

### Problem Statement Example:

> Customer churn rate has increased by 15% in the last 6 months.

OR

> Average delivery time has increased from 28 minutes to 40 minutes.

OR

> Order cancellation rate is increasing during peak hours.

---

# 4. Business Objectives

Business objectives must be:

* Clear
* Measurable
* Time-bound

### Example Objectives:

1. Reduce customer churn by 10% in 3 months.
2. Reduce average delivery time below 30 minutes.
3. Increase monthly order frequency per user from 3 to 5.
4. Reduce order cancellations by 20%.
5. Improve customer satisfaction rating from 3.8 to 4.3.

---

# 5. Translate Business Problem into Data Science Problem

### Business Question:

Why are customers leaving?

### Data Science Question:

Can we build a **customer churn prediction model** to identify users likely to leave?

---

### Business Question:

Why are deliveries delayed?

### Data Science Question:

Can we build a **delivery time prediction model**?



### Business Question:

How to increase orders?

### Data Science Question:

Can we build a **recommendation system**?


# 6. Stakeholders

Different stakeholders have different expectations.

### 1. CEO / Founders

* Revenue growth
* Market expansion
* Competitive advantage

### 2. Operations Team

* Efficient delivery routing
* Resource allocation

### 3. Marketing Team

* Targeted promotions
* Retention campaigns

### 4. Customers

* Fast delivery
* Good quality food
* Fair pricing

### 5. Delivery Partners

* Fair pay
* Optimized routes



# 7. Define Success Criteria

There are two types of success criteria:

## A) Business Success Criteria

* Revenue increase by ₹5 Crores
* Reduce churn by 10%
* Improve customer rating above 4.2

## B) Data Science Success Criteria

* Model accuracy ≥ 85%
* Precision/Recall > 0.80
* RMSE < 5 minutes (for delivery time prediction)

Business success is more important than model accuracy.



# 8. Constraints

Real-world projects have constraints.

### Technical Constraints

* Limited data
* Missing values
* No real-time system

### Financial Constraints

* Budget limitations
* Infrastructure cost

### Legal Constraints

* Data privacy laws
* User consent

### Time Constraints

* Project deadline: 2 months



# 9. Risks

Every project has risks.

* Model overfitting
* Data leakage
* Wrong assumptions
* Seasonal variations
* Biased training data

Example:
If the model is trained only on metro cities, it may fail in rural areas.



# 10. Key Performance Indicators (KPIs)

KPIs measure business health.

### Revenue KPIs

* Monthly revenue
* Average order value (AOV)

### Customer KPIs

* Customer retention rate
* Churn rate
* Customer Lifetime Value (CLV)

### Operational KPIs

* Average delivery time
* On-time delivery rate
* Order cancellation rate



# 11. Hypothesis Formation

Before building a model, form hypotheses.

Example Hypotheses:

1. Customers receiving late deliveries are more likely to churn.
2. Users who do not receive discounts order less frequently.
3. Peak-hour traffic increases delivery delay.
4. High delivery charges reduce repeat orders.

These hypotheses will later be validated using data.



# 12. Business Strategy Options

After understanding the problem, business strategies may include:

1. Dynamic pricing
2. Personalized discounts
3. Route optimization
4. Restaurant quality control
5. Loyalty programs
6. Faster grievance resolution



# 13. Alignment with Company Vision

If the company vision is:

> “Deliver happiness in 30 minutes”

Then all analytics initiatives must support:

* Speed
* Reliability
* Customer satisfaction



# 14. Final Business Understanding Summary

| Component    | Explanation                          |
| ------------ | ------------------------------------ |
| Domain       | Online Food Delivery                 |
| Problem      | High churn & delayed delivery        |
| Objective    | Reduce churn & improve speed         |
| Stakeholders | CEO, Ops, Marketing, Customers       |
| KPIs         | Churn rate, Delivery time, Revenue   |
| Constraints  | Budget, Data, Time                   |
| Risks        | Overfitting, Bias, Wrong assumptions |
| Outcome      | Data-driven decision making          |



#  Why Business Understanding is Crucial?

* Prevents solving the wrong problem
* Saves cost and time
* Aligns technical team with business goals
* Increases project success rate
* Ensures measurable ROI



