# nosql-challenge
UK Food Standards Agency - Data Analysis
Overview
The UK Food Standards Agency is a regulatory body that evaluates the food hygiene of various establishments across the UK. With the support of data provided by this agency, we aim to help the food magazine "Eat Safe, Love" determine the most interesting and relevant establishments for its upcoming articles.

Part 1: Database Setup
Steps:
Using the provided Jupyter notebook NoSQL_setup_starter.ipynb, import the establishments.json file into the database uk_food and the collection establishments.
Set up the necessary libraries: PyMongo and pprint.
Establish a connection with the MongoDB client and verify the database and collection.
Assign the establishments collection to a variable for easy access.
Part 2: Database Modification
Modifications:
Added an entry for a new halal restaurant "Penang Flavours" in Greenwich, which is pending a hygiene rating.
Updated the BusinessTypeID for "Penang Flavours" after determining the correct type for "Restaurant/Cafe/Canteen".
Removed all establishments in the Dover Local Authority based on editorial preferences.
Corrected data type inconsistencies, converting latitude and longitude to decimal numbers and RatingValue to integers.
Part 3: Exploratory Data Analysis
Key Questions:
Which establishments have the worst hygiene scores (score of 20)?
Identify establishments in London with a RatingValue of 4 or higher.
Find the top 5 establishments with the best rating (RatingValue of 5), emphasizing those with the lowest hygiene scores and in close proximity to "Penang Flavours".
Determine the distribution of establishments with the best hygiene scores (score of 0) across different Local Authority areas. Highlight the top ten areas.
For Employers
This project provides an insight into my ability to manage, modify, and analyze large datasets. I've used NoSQL databases and combined my knowledge with data analysis techniques to extract meaningful information. The results will assist "Eat Safe, Love" magazine in targeting high-quality establishments for its readers.

If you're interested in discussing this project further or exploring other ways I can contribute to your organization, please contact me at maxtravisyoung@gmail.com 







