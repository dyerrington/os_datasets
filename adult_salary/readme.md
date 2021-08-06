---
title: DB Lab 2
type: lab
duration: "1:25"
creator:
    name: Francesco Mosconi
    city: SF
---

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) DB Lab 2

## Introduction

The goal of this lab is to build a model to predict adult salary from their demographic data. The dataset comes from the [UCI Database](http://archive.ics.uci.edu/ml/datasets/Adult) and it is locally stored in a [SQLite Database](./assets/datasets/adult.sqlite).

The target variable is binary. Adults are partitioned in 2 classes with salaries above or below 50 thousand dollars.

This is an example of how data science can be useful to complement the information in our possession to produce new insights. Think for example about taking public demographic data using it for marketing or city planning.

Can you find some other industry examples where demographic data could be used to predict something?


## Exercise

#### Requirements

- Extract the data from the SQLite Database and import it in Pandas
- Decide what to do with missing values
- Explore the features distribution:
    - categorical features
    - numerical features
- Build a predictive model
- Evaluate the accuracy of the model and compare to a benchmark

**Bonus:**
- Tune the model parameters to improve the accuracy score

#### Starter code

[Starter Code](./code/starter-code/starter-code-1_4.ipynb)
> [Solution Code](./code/solution-code/solution-code-1_4.ipynb)

