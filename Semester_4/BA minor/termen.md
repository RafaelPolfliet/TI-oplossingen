# Een samenvatting van moeilijke woorden die ik niet begreep

[TOC]



:warning: Dit document is onvolledig of incorrect (de perfecte manier om martipoints te verdienen). Je weet wat je te doen staat.

#### Replicable sampling

Documentatie van Orange: 

> Replicable sampling maintains sampling patterns that can be carried across users, while stratification mimics the composition of the input data set.
>

#### Stratification

> **Stratification** is defined as the act of sorting data, people, and objects into distinct groups or layers. It is a technique used in combination with other data **analysis** tools. When data from a variety of sources or categories have been lumped together, the meaning of the data can be difficult to see.

#### Linear regression

> **Linear regression** is a way to explain the relationship between a dependent variable and one or more explanatory variables using a straight line.

#### Multiple linear regression

Hetzelfde, gewoon meerdere variabelen.

#### Lasso and ridge regression

als iemand hier een duidelijke uitleg in kan plakken: 1:moneybag: 

in de slides is het niet echt duidelijk uitgelegd

## Logistic regression

Same

Slides van ba minor:

```
General rule of thumb: for classification, start with logistic regression
```

oke bedankt

#### Logistic regression: odds

[Source](https://stats.idre.ucla.edu/stata/faq/how-do-i-interpret-odds-ratios-in-logistic-regression/)

> Let’s begin with probability. Probabilities range between 0 and 1. Let’s say that the probability of success is .8, thus
>
> **p = .8**
>
> Then the probability of failure is
>
> **q = 1 – p = .2**
>
> Odds are determined from probabilities and range between 0 and infinity. Odds are defined as the ratio of the probability of success and the probability of failure. The odds of success are
>
> **odds(success) = p/(1-p) or p/q = .8/.2 = 4,**
>
> that is, the odds of success are 4 to 1. The odds of failure would be
>
> **odds(failure) = q/p = .2/.8 = .25.**
>
> This looks a little strange but it is really saying that the odds of failure are 1 to 4. The odds of success and the odds of failure are just reciprocals of one another, i.e., 1/4 = .25 and 1/.25 = 4. Next, we will add another variable to the equation so that we can compute an odds ratio.





# Vocabulary (van Bertels)

**Supervised learning**

> the target is known (which class an instance belongs to) and a model is trained to predict that target, e.g. decision tree

**Unsupervised learning**

> the target is unknown (unknown class or even if any class structure exists) and the model seeks to uncover some hiddenclassification or structure, e.g. clustering

**Sample**

> extract a portion or subset of the data

**Oversampling**

> take multiple examples of a certain class, especially if that class is small

**Stratified sampling**

> keeping the class ratios for each sample approximately equal to the original dataset

**Discrete/Categorical**

> variable with a number of possible categories

**Numerical/Continuous**

> variable that takes any value in a range of numbers

**Outlier**

> an instance which is very different from all other examples, can mean there is an error or an interesting rare event, can skew a model’s results

**Normalize**

> adjust the scale of a variable’s values so they can be more easily compared

**Overfitting**

> training a model too closely to the training data, so it is not generalized enough to perform well on test or new data

**Training set**

> subset of the data used to train or learn a model

**Validation set**

> subset of the data used to improve the performance on a model during training

**Test set**

> subset of the data used to evaluate a model