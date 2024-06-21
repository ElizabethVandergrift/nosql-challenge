```markdown
# Eat Safe, Love: UK Food Standards Agency Data Analysis

## Overview
This project involves analyzing food hygiene ratings data from the UK Food Standards Agency. The analysis aims to help the magazine "Eat Safe, Love" focus on establishments worth featuring in their future articles.

## Instructions

### Part 1: Database and Jupyter Notebook Set Up

1. **Import Data**:
    - Import `establishments.json` into MongoDB.
    - Use the terminal command to import the data into a database named `uk_food` and a collection named `establishments`.

2. **Set Up Jupyter Notebook**:
    - Import the required libraries: PyMongo and Pretty Print (pprint).
    - Create an instance of the Mongo Client.
    - Confirm the database and collection are set up correctly by listing the databases and collections, and displaying one document from the `establishments` collection.

### Part 2: Update the Database

1. **Add a New Restaurant**:
    - Insert a new halal restaurant in Greenwich with the provided information.
    - Find the `BusinessTypeID` for "Restaurant/Cafe/Canteen" and update the new restaurant's document with this ID.

2. **Remove Establishments in Dover**:
    - Count and then remove all documents with the Dover Local Authority.
    - Verify that the documents have been removed.

3. **Convert Data Types**:
    - Convert `latitude` and `longitude` values to decimal numbers.
    - Convert `RatingValue` to integer numbers.

### Part 3: Exploratory Analysis

1. **Hygiene Score of 20**:
    - Find establishments with a hygiene score of 20.
    - Convert the results to a Pandas DataFrame and display the first 10 rows.

2. **RatingValue >= 4 in London**:
    - Find establishments in London with a RatingValue of 4 or higher.
    - Convert the results to a Pandas DataFrame and display the first 10 rows.

3. **Top 5 Establishments Near "Penang Flavours"**:
    - Find the top 5 establishments with a RatingValue of 5, sorted by the lowest hygiene score, near "Penang Flavours".

4. **Hygiene Score of 0 by Local Authority**:
    - Find the number of establishments in each Local Authority area with a hygiene score of 0.
    - Sort the results from highest to lowest and display the top 10 local authority areas.

This concludes the instructions for setting up the database, updating it, and performing exploratory analysis.
```