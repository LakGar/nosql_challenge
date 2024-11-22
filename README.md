# NoSQL-Challenge: UK Food Hygiene Ratings 🍴

## Overview

This project leverages **MongoDB** and **Python** to analyze food hygiene data from the UK Food Standards Agency. It involves setting up a NoSQL database, updating data, and performing exploratory analysis to provide insights for the food magazine **Eat Safe, Love**. The data includes ratings for establishments across the UK, helping the magazine decide where to focus future articles.

---

## Deliverables

### Part 1: Database Setup

- Import the `establishments.json` file into MongoDB, creating a database named `uk_food` and a collection named `establishments`.
- Verify successful data import by:
  - Listing all databases and collections in MongoDB.
  - Querying a sample document from the `establishments` collection.
- Prepare the collection for analysis by assigning it to a variable.

### Part 2: Update the Database

- **Add a new restaurant**: Include information for a newly opened halal restaurant, "Penang Flavours," in Greenwich.
- **Update BusinessTypeID**: Find and assign the correct `BusinessTypeID` for "Restaurant/Cafe/Canteen."
- **Remove specific data**: Delete all records associated with the "Dover Local Authority."
- **Data cleaning**:
  - Convert latitude and longitude fields from strings to decimal numbers.
  - Convert `RatingValue` fields to integers.

### Part 3: Exploratory Analysis

Answer the following questions using MongoDB queries and Python:

1. **Hygiene Score of 20**:
   - Find establishments with a hygiene score of 20.
2. **Highly Rated Establishments in London**:
   - Identify establishments in London with a `RatingValue` greater than or equal to 4.
3. **Top 5 Establishments Near "Penang Flavours"**:
   - Find the top 5 establishments with a `RatingValue` of 5, sorted by hygiene score, nearest to the new restaurant.
4. **Hygiene Score Analysis by Local Authority**:
   - Determine the number of establishments in each local authority with a hygiene score of 0. Sort the results in descending order and display the top 10.

---

## Insights and Results

- **Hygiene Score Distribution**: Identify patterns in hygiene scores to highlight clean and problematic establishments.
- **Highly Rated Locations**: Highlight the best-rated establishments in key areas like London.
- **Proximity-Based Analysis**: Compare hygiene ratings of establishments near "Penang Flavours."
- **Local Authority Insights**: Showcase authorities with the highest number of poorly rated establishments.

---

## Tools and Technologies

- **MongoDB**: NoSQL database for storing and querying data.
- **PyMongo**: Python library for MongoDB interaction.
- **Pretty Print (pprint)**: For displaying query results.
- **Pandas**: For converting MongoDB query results into DataFrames for analysis and visualization.
- **Jupyter Notebook**: For interactive development and documentation.

---

## How to Use

1. Open `NoSQL_setup_starter.ipynb` to:
   - Set up the database.
   - Perform data updates and cleaning.
2. Open `NoSQL_analysis_starter.ipynb` to:
   - Perform exploratory analysis.
   - Generate insights and visualizations.

---

## Acknowledgments

- **UK Food Standards Agency** for providing open data on food hygiene ratings.
- **MongoDB Documentation** for guidance on NoSQL queries.
- **Bootcamp Materials** for starter code and project instructions.

---

## Author

**Your Name**  
Data Scientist and Python Developer  
[GitHub](https://github.com/your-username) | [LinkedIn](https://linkedin.com/in/your-linkedin)

---

## License

This project is open source and available under the MIT License.
