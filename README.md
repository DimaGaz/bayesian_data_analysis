# bayesian_data_analysis
[_"Bayesian data analysis is an increasingly popular method of statistical inference, used to determine conditional probability without having to rely on fixed constants such as confidence levels or p-values."_](https://app.datacamp.com/learn/courses/bayesian-data-analysis-in-python) In this project, we’ll learn how Bayesian data analysis works, how it differs from the classical approach, and why it’s an indispensable part of a data science toolbox. 

These project is based on two DataCamp courses: [Introduction to Statistics in Python](https://app.datacamp.com/learn/courses/introduction-to-statistics-in-python) and [Bayesian Data Analysis in Python](https://app.datacamp.com/learn/courses/bayesian-data-analysis-in-python). The execution of the two parts will be conducted via two seperate Jupyter notebooks. 

## 1. Introduction to Statistics in Python
_"Statistics is the study of how to collect, analyze, and draw conclusions from data. It’s a hugely valuable tool that you can use to bring the future into focus and infer the answer to tons of questions"._ The datasets for this part were downloaded from the following [link](https://app.datacamp.com/learn/courses/introduction-to-statistics-in-python): Food Consumption, 2019 World Happiness Report, and  Amir's sales deals.  Alternatively, the data can be downloaded from the following [repo](https://github.com/goodboychan/goodboychan.github.io/tree/main/_notebooks/dataset).

The "Introduction to Statistics in Python" part consist of four chapters:
- __Summary Statistics__: Summary statistics gives you the tools you need to boil down massive datasets to reveal the highlights. In this chapter, we explore summary statistics including mean, median, and standard deviation, and learn how to accurately interpret them.
- __Random Numbers and Probability__: In this chapter, we learn how to generate random samples and measure chance using probability.
- __More Distributions and the Central Limit Theorem__: We explore one of the most important probability distributions in statistics, normal distribution and gain an understanding of the central limit theorem.
- __Correlation and Experimental Design__: In this chapter, we learn how to quantify the strength of a linear relationship between two variables, and explore how confounding variables can affect the relationship between two other variables.

## 2. Bayesian Data Analysis in Python
In this course, we’ll get to grips with A/B testing, decision analysis, and linear regression modeling using a Bayesian approach as we analyze [real-world advertising,  bike rental, and avocado sales data](https://app.datacamp.com/learn/courses/bayesian-data-analysis-in-python). Finally, we’ll get hands-on with the PyMC3 library, which will make it easier for us to design, fit, and interpret Bayesian models. In this chapter we will cover:
1. The Bayesian Way
    - Bayesian vs. frequentist approach
    - Probability theory & distributions
    - Updating beliefs with more data
2. Bayesian Estimation
    - Grid approximation
    - Prior distributions
    - Reporting Bayesian results
3. Bayesian Inference
    - A/B testing
    - Decision analysis
    - Forecasting & regression
4. Bayesian Linear Regression
    - Markov Chain Monte Carlo (MCMC)
    - Fitting and interpreting models with `pymc3`
    - Bayesian data analysis: a case study (separate notebbok `how_much_is_an_avocado`)
