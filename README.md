# nosql-challenge

In this assignment, the food hygiene ratings data analysis is provided for Eat Safe, Love magazine. The goal was to assist their journalists and food critics in determining the establishments to focus on for future articles. The analysis utilized a MongoDB database and Jupyter Notebook.

The initial step involved setting up the database by importing the food hygiene ratings data from the UK Food Standards Agency. Subsequently, requested modifications were implemented, including field renaming and conversion of rating data to a more usable format.
to importing the database after navigating to the directory where the JSON database file is located, using the mongoimport command to import the JSON file into mongoDB as below:
mongoimport -d uk_food -c establishments --type json --jsonArray establishments.json
Using the updated database, exploratory analysis was performed to address specific inquiries posed by the magazine. This encompassed examining rating distributions, identifying top-rated establishments, analyzing geographic locations, and applying filters based on establishment type.

