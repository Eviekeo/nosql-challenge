# nosql-challenge

# Background 
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

As part of this challenge, I have imported data in MongoDB, and analysed the data in python using PyMongo. 

# Directory
The repository includes the following two jupyter notebooks:
- NoSQL_setup_starter.ipynb: this notebook contains code used to access the Mongo database using PyMongo, update the database with a new document and change the data type from string to decimal for the longitute and latitude fields within the documents
- NoSQL_analysis_starter.ipynb: this notebook contains code used to analyse the data by focusing on the following 4 research topics:
    1. Establishments with a hygiene score equal to 20
    2. Establishments in London with a RatingValue greater than or equal to 4
    3. Top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, and nearest to the new restaurant "Penang Flavours"
    4. Top 10 establishments in each Local Authority area with a hygiene score of 0, sorted from highest to lowest