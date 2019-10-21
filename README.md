# Feature_Engineering
Introduction to Data Science - Project 2. 
Source of Data: https://www.kaggle.com/kingburrito666/shakespeare-plays/download
STEP_1:
Importing the csv dataset and loading it as a pandas dataframe

STEP_2: DATA CLEANINING/PREPROCESSING
Removing all the records for which either of the PlayerLinenumber, ActSceneLine or Player is NaN

STEP_3: FEATURE ENGINEERING
Task: To classify the plays into categories of 16th Century Play or 17th Century Play.
 Step 3.1: Get all the unique values of the Plays (from the 'Play' Column)
 Step 3.2: Create a new custom feature called 'Year' using the function create_year_of_play() and applying it on the 'Play'    feature/column using apply() method.
 Step 3.3: Write a function period_of_play() to classify the plays into categories of four periods of Shakespeares' plays.    This function is applied on the newly developed custom feature 'Year'.
 Step 3.4: Write a function century_of_play() to classify the plays into categories of century. This function is applied on the newly developed custom feature 'Year'.

STEP_4: Get Data insights after feature engineering
 1. Plays per year
 2. Plays per period of writing
 3. Players/Actors/Characters per play
 4. Characters in most number of scenes, ordered by period of writing
