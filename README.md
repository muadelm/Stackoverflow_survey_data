# Stackoverflow_survey_data

**Installations**
The project is on predicting the salary of programmers based on the StackOverFlow survey done in 2017.

The libraries used are:
	
	pandas
	
	numpy
	
	seaborn
	
	random
	
	sklearn
	
	matplotlib
	
	missingno
	
**Project Motivation**
The project is part of Udacity data Science nano-degree and is directed towards answering the following three questions:

1) In Which countries people earned more than the rest.

2) What is the relation between salary and eduction in these counries.

3) How to forecast the salary based on the survey data considering categrical data like country and eduction level?

**File description**

The analysis will follow the CRISP-DM steps:

1) Business Understanding

2) Data Understanding (access and explore)

3) Data cleaning and preparation of some categotrical columns into dummies to go into a linear model

4) Linear modeling

5) Evaluation

6) Deployment

**Takeaways and summary fo teh analysis**

`1-` The majority of respondents to the survey came from 10 countries; United States, India, United Kingdom, Germany, Canada, France, Poland, Australia, Russian Federation, and Spain. Programers in the United States earned the most while India and Russia earned the lowest.

`2-` The salary of a programmer is not related to education level as many earned more through a university degree. This could highlight the role of online education in building competent skillsets.

`3-` Our linear regression model that relied mainly on education, country and company size did not manage to predict salaried above $50,000 with good accuracy. More feature engineering work is required to enhance model performance.

**Author:**
Mustafa Adel Amer
