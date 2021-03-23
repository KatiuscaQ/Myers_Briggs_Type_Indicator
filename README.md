# Myers-Briggs Personality Type Indicator

## Project Overview

This project is based on this [Kaggle dataset](https://www.kaggle.com/datasnaek/mbti-type).

The last 50 tweets from various accounts on Twitter were gathered (column: “posts”) and a Myers-Briggs Personality Type was assigned (column “type”). Using Machine Learning (SVM, Random Forest, and Neural Networks), the dataset was analyzed to see if we could correctly predit the personality type based on their tweets.

### Myers-Briggs Personality Type

“The purpose of the Myers-Briggs Type Indicator® (MBTI®) personality inventory is to make the theory of psychological types described by C. G. Jung understandable and useful in people's lives. The essence of the theory is that seemingly random variation in behavior is actually quite orderly and consistent, being due to basic differences in the ways individuals prefer to use their perception and judgment.” -[Source](https://www.myersbriggs.org/my-mbti-personality-type/mbti-basics/)

The MBTI divides people’s personalities into 16 personality types, across 4 axes:

### •	Extroverted/Introverted (E/I):
This axis differentiates where a person gets their energy from:
-	Extroverts gain energy from being around other people: talking, conversing, being noticed, etc. They can be alone but will get tired without contact.
-	Introverts gain energy from being alone and clearing their thoughts. Opposite to extroverts, introverts have the capability to socialize quite effectively; but their alone time is a must.

### •	Intuitive/Sensory (N/S):
Here, the differences lie in how the individual perceives their world. 
-	Intuitives (N) prefer speculation and depth of insight, they are better at perceiving the world through their mind and imagining abstract possibilities in the world.
-	Sensors (S) prefer tangible information, they are better at perceiving the world through the five senses.

### •	Thinking/Feeling (T/F):
This domain deals with how the individual judges the information they have perceived.
-	Thinkers (T) apply logical reasoning, make decisions using impersonal criteria, and focus on tasks.
-	Feelers (F) apply individual values, make decisions by personal circumstances, and focus on relationships.

### •	Judgmental/Perceiving (J/P):
This domain basically states whether the perceiving trait or the judging trait is the dominant trait of the individual.
-	Judgers (J) tend to like a planned and organized approach to life, prefer to have things settled, and enjoy structure.
-	Perceivers (P) tend lo like a flexible and spontaneous approach to life, prefer to keep their options open, and enjoy freedom.

The 16 personality types are:


![The_Ambassadors_png](https://github.com/KatiuscaQ/Myers_Briggs_Type_Indicator/blob/main/Resources/The_ambassadors.PNG)

![The_Thinkers_png](https://github.com/KatiuscaQ/Myers_Briggs_Type_Indicator/blob/main/Resources/The_thinkers.PNG)

![The_Guardians_png](https://github.com/KatiuscaQ/Myers_Briggs_Type_Indicator/blob/main/Resources/The_guardians.PNG)

![The_Explores_png](https://github.com/KatiuscaQ/Myers_Briggs_Type_Indicator/blob/main/Resources/The_explorers.PNG)


*Disclaimer: illustrations taken from [here](https://www.16personalities.com/personality-types)*


## Hypothesis:

•	Ho = Someone’s personality can be determined by their tweets.

•	Ha = Someone’s personality cannot be determined by their tweets.

The goal is to build a machine learning algorithm that attempts to determine someone’s personality based on their tweets.

## Technology 

The technology choseen for this project can be found [here](https://github.com/KatiuscaQ/Myers_Briggs_Type_Indicator/blob/main/technology.md)
 
## Database

The preprocessed database can be found [here](https://github.com/KatiuscaQ/Myers_Briggs_Type_Indicator/blob/main/preprocess_data.ipynb)

## Machine Learning Model

Three different types of Machine Learning models were used. These are widely applied for their success when working with Natural Language Processing (NLP):

* [Random Forest](https://github.com/KatiuscaQ/Myers_Briggs_Type_Indicator/blob/main/Machine%20Learning.ipynb) 
* [Neural Network](https://github.com/KatiuscaQ/Myers_Briggs_Type_Indicator/blob/main/Machine%20Learning.ipynb)
* [Linear Support Vector Machine (supervised learning)](https://github.com/KatiuscaQ/Myers_Briggs_Type_Indicator/blob/main/SVM_Prototype.ipynb)


## Dashboard 

Through the use of Tableau Public, an interactive dashboard to showcase our project and ML results will be used by our viewers. The dashboard will allow the viewer to find out which personality type they are and in turn, see commonly used words by that personality. The ETL process of the data provided many useful charts and images to showcase such as the distribution of Myer-Briggs Personality Types in the Dataset, Top 25 Word Frequencies Used, and word clouds. 

Click the link [here](https://public.tableau.com/profile/christopher.guilcapi3266#!/vizhome/PersonalityAnalysis/Dashboard1?publish=yes) to explore the live Tableau Public Dashboard:

![](/Resources/Tableau_logo.jpeg)






