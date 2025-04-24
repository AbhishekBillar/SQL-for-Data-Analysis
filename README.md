# Task 3: SQL for Data Analysis - movies_dataset

This repository contains SQL queries used to analyze a movie dataset that includes movies, financials, actors, and languages. The analysis covers a variety of tasks like filtering, grouping, joining tables, and performing calculations to extract useful insights from the data.

## SQL Queries Performed:

1. **Movies Released After 2015 with IMDb Rating Above 7**: 
   - Filtered movies released after 2015 with an IMDb rating above 7.
   - Ordered them by rating in descending order.

2. **Movies Released Each Year**:
   - Counted how many movies were released each year.
   - Grouped the data by year.

3. **Movies in Each Industry**:
   - Counted the total number of movies in each industry.
   - Ordered the industries by the number of movies.

4. **Total Revenue for Hollywood**:
   - Calculated the total revenue for movies in the 'Hollywood' industry in USD (millions).

5. **Average IMDb Rating of Movies**:
   - Calculated the average IMDb rating for all movies in the dataset.

6. **Movies and Their Languages**:
   - Used an INNER JOIN to list movies with their corresponding language names.

7. **Movies in Each Language**:
   - Used a LEFT JOIN to show all languages and the number of movies made in each language.

8. **Movie with the Second Highest IMDb Rating**:
   - Identified the movie with the second-highest IMDb rating.

9. **Average Budget for Movies with Above Average Revenue**:
   - Calculated the average budget for movies with revenue above the average.

10. **View for Total Revenue by Industry**:
    - Created a view to analyze total revenue per industry (focusing on Hollywood).
   
11. **Index Creation for Faster Joins**:
    - Created an index on the `movie_id` in the `financials` table to optimize join operations.

## What I Learned:

- **Filtering and Sorting**: Learned how to filter data based on specific conditions like year and rating, and how to order results.
- **Grouping and Aggregation**: Gained experience in grouping data and using aggregation functions like `COUNT()` and `SUM()`.
- **Joins**: Improved my skills in joining multiple tables using `INNER JOIN` and `LEFT JOIN` to combine related data.
- **Subqueries**: Used subqueries to get the second-highest IMDb rating and calculate averages.
