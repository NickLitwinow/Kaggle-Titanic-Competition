![download (1)](https://user-images.githubusercontent.com/44932745/209876075-f8202d29-d33d-4010-9442-1342e0a1cd5e.png)


# Kaggle Titanic Project

(https://www.kaggle.com/code/nicklitwinow/titanic-max-accuracy-0-77033)

This project addresses the Kaggle Titanic challenge, where the goal is to predict passenger survival based on a variety of features. The current solution achieved a maximum accuracy rate of 0.77033.

## Project Overview

The sinking of the Titanic is one of the most infamous maritime disasters in history. On April 15, 1912, the RMS Titanic sank after colliding with an iceberg. This project aims to determine which groups of people were more likely to survive using passenger data. The solution involves:
- Data cleaning and preprocessing: filling missing values, dropping irrelevant features, and transforming data.
- Exploratory Data Analysis (EDA): generating histograms, count plots, and correlation heatmaps to understand the data.
- Modeling: training a Random Forest Regressor to predict survival and generating a submission file.

## Data Description

The dataset consists of the following key files:
- **train.csv**: Training data including 891 records with features such as PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, and Embarked.
- **test.csv**: Test data containing 418 records without the target variable (`Survived`).
- **gender_submission.csv**: A template file used to create the final submission.

Key fields include:
- **Survived**: Target variable (0 = No, 1 = Yes).
- **Pclass**: Passenger class (1st, 2nd, or 3rd).
- **Sex** and **Age**: Demographic details.
- **SibSp** and **Parch**: Family information.
- **Fare**: Passenger fare (transformed using a cube root transformation).
- **Embarked**: Port of embarkation.
