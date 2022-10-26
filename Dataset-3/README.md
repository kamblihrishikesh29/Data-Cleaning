
# Dataset Description

## Overview
The data has been split into two groups:

training set (train.csv)
test set (test.csv)'

The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger.

The test set should be used to see how well your model performs on unseen data.

## Data Dictionary <br>

![image](https://user-images.githubusercontent.com/64286223/198135867-9d1a0c07-6df3-409f-b3be-f00068cd9320.png)

#### Variable Notes
pclass: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.
