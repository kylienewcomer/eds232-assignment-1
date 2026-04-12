# Homework 1 Task 3

---

Answer the following questions based on exercises from *An Introduction to Statistical Learning with Applications in Python*.

## Chapter 2.4 Exercises

---

### Exercise 1 (ISLP exercise 2)

Explain whether each scenario is a **classification or regression** problem, and indicate whether we are most interested in **inference or prediction**. Finally, provide **n** (size of observation dataset) and **p** (number of predictors).

**(a)**  We collect data on 200 protected marine reserves worldwide. For each reserve we record species richness, reserve size, years since establishment, enforcement budget, and proximity to human settlements. We are interested in understanding which factors affect species richness.

> This is regression problem, because we are assessing biodiversity. We would be more interested in inference, to determine which factors are most influential on species richness.
size of observations (n) = 200
number of predictors (p) = 4

---

**(b)** A conservation agency wants to know whether a proposed habitat corridor will successfully support wildlife movement or fail to do so. They collect data on 30 previously established corridors. For each corridor they have recorded whether wildlife movement was successful or unsuccessful, corridor width, length, surrounding land use type, and eight other variables.

> This would be considered a classification problem, because we are determining whether or not an outcome occurred. We would be more interested in prediction, because we are predicting whether or not the intervention will be successful.
n = 30
p = 11

---

**(c)** We are interested in predicting weekly average ground-level ozone concentration in a coastal city. We collect weekly data for all of 2019. For each week we record average ozone concentration, sea surface temperature, wind speed, solar radiation, and atmospheric

> This would be a regression, because we are modeling ozone concentration. We would focus on prediction to forecast ozone concentrations. 
n = 52
p = 4

---

### Exercise 2 (ISLP exercise 5)

What are the advantages and disadvantages of a very flexible (versus a a less flexible) approach for regression? Under what circumstances might a more flexible approach be preferred to a less flexible approach? When might a less flexible approach be preferred?

> One advantage of a flexible model is that it is able to capture non-linear relationships. It fits to the data better, however there is potential to overfit the model. It can also have more variance. The advantage of a less flexible model is a simpler interpretation and less variance. It does have the risk of underfitting the data. 

It is better to use a more flexible model when the relationship between the predictor and outcome is non-linear. 
Less flexible models are better for smaller sample sizes or simpler relationships between variables.

---

### Exercise 3 (ISLP exercise 6)

Describe the differences between a **parametric** and a **non-parametric** statistical learning approach. What are the **advantages** of a parametric approach to regression or classification (as opposed to a non-parametric approach)? What are its **disadvantages**?

A parametric approach assumes the shape of the model whereas non-parametric does not. It can be advantageous to use a parametric approach if the data is smaller, however, if the model may be a poor fit if it's not assumed correctly. It is also less flexible than a non-parametric approach.