# nosql_challenge
# Part 1 Database and Jupyter Notebook Set Up
- Import the dataset with `mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`
  - Create the database uk_food
    - with collection establishments
# Part 2 Update the Database
- Add a new restaurant names "Penang Flavours"
  - Insert new restaurant into database
# Part 3 Exploratory Analysis
- Find establishments with a hygiene score equal to 20
- Find establishments in London with a RatingValue greater than of equal to 4
- Find the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest new restaurant added "Penang Flavours"
- Find establishments in each Local Authority that have a score of 0
