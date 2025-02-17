# **Analysing UK Food Hygiene Ratings**
<img src="images/food.JPG" width="1000" height="491">

## Introduction
In this analysis, I delve into UK Food Hygiene Ratings data to assist Eat Safe, Love magazine. With the aim of guiding their food critics, I explore establishments' ratings, focusing on hygiene, location, and scores. Through MongoDB, I initiate the database setup, load data, and make necessary updates. Subsequently, I tackle exploratory queries, such as identifying hygiene scores of 20, high-rated establishments in London, top-rated eateries near "Penang Flavours," and localities with hygiene score 0. My goal is to uncover valuable insights, guiding the magazine's content selection and ensuring readers' food safety awareness.

**Part 1: Database and Setup**
1. Import the data from establishments.json into the "uk_food" database and the "establishments" collection. 
2. Import necessary libraries: PyMongo and Pretty Print (pprint).
3. Create a Mongo Client instance.
4. Confirm the presence of the "uk_food" database and the "establishments" collection.
5. Display a sample document using find_one() and pprint().
6. Prepare the "establishments" collection for analysis.

**Part 2: Update the Database**
1. Add a new halal restaurant's information to the database.
2. Find and update the BusinessTypeID for "Restaurant/Cafe/Canteen".
3. Count and remove establishments in the Dover Local Authority.
4. Convert latitude and longitude to decimal numbers.

**Part 3: Exploratory Analysis**
Use "NoSQL_analysis_starter.ipynb" to explore the dataset and answer the following questions:

1. **Hygiene Score of 20:** Count, display, and convert establishments with a hygiene score equal to 20.
2. **RatingValue in London:** Count, display, and convert establishments in London with a RatingValue greater than or equal to 4.
3. **Top 5 Establishments with RatingValue 5:** Count, display, and convert the top 5 establishments with RatingValue '5', sorted by lowest hygiene score and proximity to "Penang Flavours".
4. **Local Authority Areas with Hygiene Score 0:** Count, sort, and display the top ten local authority areas with establishments having a hygiene score of 0.

