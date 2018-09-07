# Project1

ACADGILD-DATA-SCIENCE-Project-1
PROJECT 1

1.​ ​Introduction This assignment will help you to consolidate the concepts learnt in the session.

2.​ ​Problem Statement

import pandas as pd import numpy as np import matplotlib.pyplot as plt %matplotlib inline df = pd.read_csv('​https://raw.githubusercontent.com/jackiekazil/data-wrangling/master/dat a/chp3/data-text.csv​') df​.head(2) df1 = pd.read_csv('​https://raw.githubusercontent.com/kjam/data-wrangling-pycon/master/d ata/berlin_weather_oldest.csv​') df1​.head(2)

Get the Metadata from the above files. Expected Output:

Get the row names from the above files. Expected Output:

Change the column name from any of the above file. Expected Output:

Change the column name from any of the above file and store the changes made permanently. Expected Output:

Change the names of multiple columns. Expected Output:

Arrange values of a particular column in ascending order. Expected Output:

Arrange multiple column values in ascending order. Expected Output:

Make ​country​ as the first column of the dataframe. Expected Output:

Get the column array using a variable Expected Output:

Get the subset rows 11, 24, 37 Expected Output:

Get the subset rows excluding 5, 12, 23, and 56 Expected Output:

Load datasets from CSV users = pd.read_csv('​https://raw.githubusercontent.com/ben519/DataWrangling/master/Data/ users.csv​') sessions = pd.read_csv('​https://raw.githubusercontent.com/ben519/DataWrangling/master/Data/ sessions.csv​') products = pd.read_csv('​https://raw.githubusercontent.com/ben519/DataWrangling/master/Data/ products.csv​') transactions = pd.read_csv('​https://raw.githubusercontent.com/ben519/DataWrangling/master/Data/ transactions.csv​') users.head() sessions.head() transactions.head()

Join users to transactions, keeping all rows from transactions and only matching rows from users (left join) Expected Output:

Which transactions have a UserID not in users? Expected Output:

Join users to transactions, keeping only rows from transactions and users that match via UserID (inner join) Expected Output:

Join users to transactions, displaying all matching rows AND all non-matching rows (full outer join) Expected Output:

Determine which sessions occurred on the same day each user registered Expected Output:

Build a dataset with every possible (UserID, ProductID) pair (cross join) Expected Output:

Determine how much quantity of each product was purchased by each user Expected Output:

For each user, get each possible pair of pair transactions (TransactionID1, TransacationID2) Expected Output:

Join each user to his/her first occuring transaction in the transactions table Expected Output:
