# Titanic_EDA
<p>Exploratory data analysis for Titanic EDA, this is done to satisfy the requirements for the first project in the Udacity Data Scientist Nanodegree.</p>

### Table of Contents
- [Installation](#installation)
- [Motivation](#motivation)
- [Dataset](#dataset)
- [File Descriptions](#file-descriptions)
- [Analysis Results](#analysis-results)
- [Acknowledgements](#acknowledgements)



## Installation 
There are no libraries needed other than the one included in Anaconda distribution and the Python version used is version 3.

## Motivation 

In this project, the Titanic dataset was used to understand how different factors played in the survivial of the passengers.<br> 
5 Questions were defined: <br>

1. What is the surviving rate in terms of gender and class?<br>
2. Were married women more likely to survive than unmarried women?<br>
3. Which age group were the highest in each passenger class ?<br>
4. What is the surviving rate in each age group ?<br>
5. Is there a correlation between the surviving rate and the number of relatives for each passenger?<br>


## Dataset

The dataset was acquired from Kaggle. two files can be found in Kaggle the one used for this EDA is the training dataset
since the testing dataset is missing the "Survived" column. The dataset contains 891 rows and 12 columns.<br>

#### Features:<br>

1. PassengerId<br>
2. Survived: Whether a passenger survived the sinking or not. 0 for no , 1 for yes.<br>
3. Pclass: Ticket Class. It indicates the Socioeconomic status of the passenger. 1 for upper class, 2 for middle class, 3 for lower class<br>
4. Name<br>
5. Sex<br>
6. Age <br>
7. SibSp: Number of siblings and spouse aboard the ship. <br>
8. Parch: Number of parents and children aboard the ship.<br>
9. Ticket<br>
10. Fare: Passenger fare <br>
11. Cabin: Cabin number<br>
12. Embarked: Port of Embarkation. There are three ports C:Cherbourg, Q:Queenstown and S:Southampton. <br>

Three features were extracted:<br>

1. Married: this feature is only for the female passengers. It was extracted from the name of the passenger which contianed the social title. Miss for unmarried women, Mrs for married women.<br>
2. Age group: 4 Age groups were defined and mapped according to each passenger age in this column.<br>
0-18 years old , 19-40 years old, 41-60 yeard old, 60+ years<br>
3. Relatives: The number of siblings/spouse and parents/children combined.

## File Descriptions
The repository contains 2 files, the dataset in a csv format and one jupyter notebook that explores the data and answer
the questions mentioned above.

## Analysis Results 

The results of the exploratory data analysis can be found in the following post [here](url for the post) 

## Acknowledgements
[Seaborn Documentation](https://seaborn.pydata.org)<br>
[Pandas Documentation](https://pandas.pydata.org/docs/) <br>
the dataset was Acquired from Kaggle, All information about the licensing can be found in the following [link](https://www.kaggle.com/c/titanic)<br>



