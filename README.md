# NOSQL-challenge Eat Safe, Love

Using PyMongo through Mongo client to analyze food establishments across the UK for Hygiene ratings. The process included updating database and exploratory analysis.

# Contents of Repository
Resources folder
  - establishments.json file
NoSQL_analysis_MRSmith.ipynb
NoSQL_EatSafeLove_MRSmith.ipynb

The database was updated by inserting a document into the collection and deleting certain documents. Rating values were updated and certain field types were converted appropriately. Queries were performed to confirm updates as well as to query for certain criteria to answer the questions below. The results for each analysis used to answer the questions were converted to Pandas DataFrame.

# Analysis answered the following questions:
1) Which establishments have a hygiene score equal to 20?
2)  Which establishments in London have a RatingValue greater than or equal to 4?
3)  What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4)  How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

# References
UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
