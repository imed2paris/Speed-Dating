# Speed dating


## Topic

* The aim of this project is to perform an exploratory data analysis in which we will use appropriate data visualisation methods.
* The dataset includes data collected during 21 speed dating events that took place between October 2002 and April 2004.
* The data concern different aspects of these events:
    * data on the organisation (number of people met, number of the starting position at the event, number of the date when meeting the partner, etc.)
    * data on the participant (gender, age, race, field of study, intended career, etc)
    * data filled in by the participant at different times (seductive attributes to be noted, decision to meet the partner again, impression of the duration of the meetings, etc)
* You can find more details by clicking [here](https://www.kaggle.com/annavictoria/speed-dating-experiment)


## Objective

* We will see if we can discover the secret of love by analysing the most relevant features collected during all these speed dating sessions.
* We will focus on the differences between women and men.
* We will cross the features with the dichotomous variable "match" (1 if there is a match, 0 if there is not) in order to be able to extract some patterns that might explain why two people are willing to meet a second time.


## Issues

* The dataset contains a lot of variables (just under 200): it is useful to consider deleting some data fields.
* The number of people participating in the event is not the same from one session to another. 
* The dataset contains data collected at different times around the speed dating event: this is why we decided to separate the dataset into several tables after removing the less relevant features.
* There are more than 8000 records corresponding to 551 participants: care must be taken when selecting the data to be visualised, as there is a risk of counting the same data several times.


## Technologies

* I use python packages to explore the dataset : 
    * Pandas for data wrangling, 
    * Seaborn and Matplotlib for data visualization.