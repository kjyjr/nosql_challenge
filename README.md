# nosql_challenge

This assignment involved evaluation of food hygiene ratings given by the UK Food Standards Agency for various restaurants across the United Kingdom. Evaluation of the ratings was done under the guise of being contracted by editors of a food magazine to help their journalists and food critics decide their focus for future articles.

The assignment was divided into three parts: 1) database and Jupyter notebook set-up, 2) update of the database, and 3) exploratory analysis of the data. In addition to the Jupyter notebook, also used were PyMongo and Pretty Print.

In the first part of the assignment, a database and its collection on UK restaurants were created in MongoDBCompass, and restaurant ratings data then loaded into the database collection.

In part two, updates were made to the dataset to include a new restaurant and to exclude others in a particular local authority.

In part three, the modified dataset was analyzed to assist the magazine editors with finding locations to visit and ones to avoid. Specific questions to be answered were:
•	Which establishments have a hygiene score equal to 20?
•	Which establishments in London have a rating value greater than or equal to 4?
•	What are the top 5 establishments with a rating value of 5, sorted by lowest hygiene score, nearest to the new restaurant that was added to the dataset.
•	How many establishments in each Local Authority area have a hygiene score of 0 (results sorted from highest to lowest)?
