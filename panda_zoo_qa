# PandaZoo code

## Question 1
# Import numpy
import numpy as np

## Question 2
# Import pandas
import pandas as pd

## Question 3
# Import matplotlib.pyplot
import matplotlib.pyplot as plt

## Question 4
# Read in the titanic3.xls data set and call it titanic_df
titanic_df = pd.read_excel('titanic3.xls', 'titanic3', index_col=None, na_values=['NA'])

## Question 5
# Use head function to look at the titanic_df dataset
titanic_df.head()

## Question 6
# Use describe function to learn more about the titanic_df dataset
titanic_df.describe()

## Question 7
# Drop the 'ticket', 'cabin', 'boat', and 'body' columns from data set
titanic_df = titanic_df.drop(['ticket','cabin','boat','body'], axis=1)

## Question 8
# Let's make a bar plot on the survived column using value counts
pd.value_counts(titanic_df['survived']).plot.bar()

## Question 9
# Let's have a look at the mean of the people that survived, i.e the 'survived' column.
titanic_df['survived'].mean()

## Question 10
# Let's group our data by the sex of the passenger and see what the means are.
titanic_df.groupby(['sex']).mean()

## Question 11
# Let's group the data by sex and class of the passenger and see what the means are.
titanic_df.groupby(['sex','pclass']).mean()

## Question 12
#  Let's look at the sex and the class but only look at those under 18 years old and see what the means are.
titanic_df[titanic_df['age']<18].groupby(['sex','pclass']).mean()











