# NoSQL-Challenge
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## Part 1: Database and Jupyter Notebook Set Up:
Use NoSQL_setup_starter.ipynb for this section of the challenge.

  1. Import the data provided in the establishments.json file from your Terminal. Name the database uk_food and the collection establishments. Copy the text you used to import your data from your Terminal to a markdown cell in your notebook.

  2. Within your notebook, import the libraries you need: PyMongo and Pretty Print (pprint).

  3. Create an instance of the Mongo Client.

  4. Confirm that you created the database and loaded the data properly:

  5. List the databases you have in MongoDB. Confirm that uk_food is listed.
  6. List the collection(s) in the database to ensure that establishments is there.
  7. Find and display one document in the establishments collection using find_one and display with pprint.
  8. Assign the establishments collection to a variable to prepare the collection for use.
  
## Part 2: Update the Database: 
Use NoSQL_setup_starter.ipynb for this section of the challenge.
The magazine editors have some requested modifications for the database before you can perform any queries or analysis for them. 

## Part 3: Exploratory Analysis
Eat Safe, Love has specific questions they want you to answer, which will help them find the locations they wish to visit and avoid.
![The first 5 rows](https://user-images.githubusercontent.com/116124181/216494276-b5f55736-262f-4030-9a7c-44a71e42f50d.png)
