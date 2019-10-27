# Mobile App Project

## Source Description
 The dataset is a mobile game dataset from kaggle that was pulled via iTunes API in August 2019. The dataset contains ~17,000 mobile games on the iTunes app store.

## Big Question
What makes one app more popular than another? Is there an interaction with the cost of an app and other features? We will try and explore these relationships in order to better understand the operating characteristics of highly rated apps!


For this dataset, I would like to conduct a effect measure modification analysis of the number of provided languages in an app and the price.

-   Requirements A: A column with the numeric number of provided languages in an app

-   Preface for Requirement B:
-   *Interaction* is the *product of two variables A x B*
-   We can then calculate the likelihood ratio on a linear model without the interaction column and another model with the interaction column. This will help us determine the effect.

-   Requirements B: A column that will calculate the interaction of language and price
