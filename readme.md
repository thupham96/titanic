# Titanic
## by Thu Pham


## Dataset

>  The sinking of the Titanic is one of the most infamous shipwrecks in history.
>  On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.
>  While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.
> In this project, I will use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

## Important Findings

- For this project, I have chosen Ticket Class (Pclass), Age, Port of Embarkation (Embarked_Coded), Sex, and Family variables to build classification models. Family is the combination of number of siblings/spouses (sibsp) and number of parents/children (parch). There is a little imbalance in data which can cause bias in prediction such as there were more male passengers than female passengers. Most of them were solo travelers, embarked from port Southampton, and bought 3rd class ticket. There is also a little right skew in the distribution of age.
- Logistic regression is a classification algorithm used to find the probability of event success and event failure. It is used when the dependent variable is binary(0/1, True/False, Survived/Not Survived) in nature. The Logistic Regression model in this project returns 77% accuracy on the test set.
- A Naive Bayes classifier is a probabilistic machine learning model that is used for classification task. The classifier is based on the Bayes theorem. The Naive Bayes model in this project returns 76% accuracy.


## Credits

Kaggle (https://www.kaggle.com/c/titanic)
