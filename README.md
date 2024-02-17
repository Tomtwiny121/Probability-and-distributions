# Probability and Distributions

**© ExploreAI Academy**

In this notebook, we'll cover statistical concepts, probability, and different types of distributions that can be used to analyze data using the `scipy.stats` package script in Python.

## Learning Objectives
By the end of this notebook, you should be able to:

- Distinguish between inferential and descriptive statistics.
- Describe and identify the different variables and data types.
- Utilize the `scipy.stats` package in Python.
- Understand the concepts of random variables.
- Understand probability functions.
- Differentiate and explain different distributions.

## Table of Contents
- [Descriptive and Inferential Statistics](#descriptive-and-inferential-statistics)
- [Variables and Data Types](#variables-and-data-types)
- [Probability – the Chance of Everything Happening](#probability--the-chance-of-everything-happening)
- [Probability Mass and Probability Density Functions](#probability-mass-and-probability-density-functions)
- [Distributions in Statistics](#distributions-in-statistics)
  - [Normal Distribution](#normal-distribution)
  - [Binomial Distribution](#binomial-distribution)
  - [Poisson Distribution](#poisson-distribution)
  - [Negative Binomial Distribution](#negative-binomial-distribution)
  - [Exponential Distribution](#exponential-distribution)
  - [Uniform Distribution](#uniform-distribution)

## Descriptive and Inferential Statistics

The two main branches of statistics are descriptive and inferential statistics.

The best comparison between the two is described in Keone Hon's Introduction to Statistics: "Descriptive statistics is used to say something about a set of information that has been collected only. Inferential statistics is used to make predictions or comparisons about a larger group (a population) using information gathered about a small part of that population. Thus, inferential statistics involves generalizing beyond the data, something that descriptive statistics does not do."

### Descriptive Statistics

Descriptive statistics summarize and describe the main features of a dataset. This includes measures of central tendency (mean, median, mode) and measures of variability (range, variance, standard deviation).

Let's examine a simple dataset on deforestation rates in various regions to calculate basic descriptive statistics for the year 2020.
