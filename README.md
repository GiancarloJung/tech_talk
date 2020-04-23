# Tech Talk I

---

## Introduction

In this presentation I will explain the basic concepts behind data analysis and machine learning.

## Review

In order to understand the concepts that we are going to study here we need to first review a few math concepts

### Probability

Probability is a numerical description of how likely an event is to occur or how likely it is that a proposition is true.

Probability is a number between 0 and 1, where, roughly speaking, 0 indicates impossibility and 1 indicates certainty.

### A Priori Probability

Analysis of the events and the ways that they occur

Examples:

- Roll of Dices

- A game of Blackjack

### Empirical Probability

Measuring of a event in order to determine its probability

Examples:

- Uptime of a service

- Failed jobs


---

## Machine Learning

---

## Introduction

"AI is a computer system able to perform tasks that ordinarily require human intelligence.

Many are powered by machine learning, some of them are powered by deep learning and some of them are powered by very boring things like rules."

Jeremy Achin


### So what is Machine Learning

Machine Learning is a field of artificial intelligence often called Narrow AI. Its focus is to use **statistical techniques** to help a system to be progressively better at a task, without the need to specifically program it to do so.

There are two main areas inside the study of Machine Learning:

- Supervised learning (using labeled datasets)

- Unsupervised learning (using unlabeled datasets)

### Algoritms

- Machine learning:

  We can say that machine learning program is a algorithm that trained to perform one task extremely well  

  We can divide machine learning into two types of algorithm based on its utilization

- Regression

  Regression its the core for prediction, it looks for relationships between your data.

- Classification

  Uses prediction to sort data, or to apply a label to a given input


### Linear Regression

The term *linearity* in algebra refers to a linear relationship between two or more variables. If we draw this relationship in a two-dimensional space we get a straight line.

A **linear relationship** basically means that when one or more independent variables increases (or decreases), the dependent variable increases (or decreases) too.

### Equation

#### y = mX + b

[ picture of the function ]

- Y is the dependent variable (or the variable we are trying to predict or estimate);

- X is the independent variable (the variable we are using to make predictions);

- m is the slope of the regression line, it represent the effect X has on Y, example:

  **Y = mx + b**

  *Y = 2x + 4*
  *(1, 6)*
  *(2, 8)*
  *(3, 10)*

  It also is a number that describes both the direction and the steepness of the line.

- b is a constant, the intercept in the Y axis when x is 0;

We won’t always know the exact relationship between X and Y, for that we use Linear Regression (LR).

In a (LR) model, we build a model based on data, meaning that the slope and Y-intercept derive from the it.


```
# install anaconda and jupyter-notebook

$ mkdir tech_talk && cd tech_talk

$ jupyter notebook

# this opens jupyter on your browser where
# we can start exploring
```

---

### Where to start?

- blog.usejournal.com/how-does-switching-from-web-development-to-machine-learning-feel-like-9ac7a370e751

- coursera.org/learn/machine-learning

- Book: Practical Statistics for Data Scientists
