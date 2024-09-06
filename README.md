The aim of this small project is to enhance and to showcase my SQL skills through the analysis of a database from the most popular website dedicated to the hobby of Board Games.

For this analysis I only looked at the top 5000 games by ranking.

Each section of the analysis intends to investigate a different premise, and in each one you can find a summary of the aim of that section's analysis as well as a small conclusion of the results of the queries. Below, you can find an overview of the types of queries performed in each section:

Most Popular Mechanics: ALTER TABLE, ALTER COLUMN, WITH ... AS(), JOIN, data type conversion using "::"

Number of Mechanics and Complexity: CASE, ROLLUP, ALTER TABLE, ADD COLUMN, UPDATE/SET, ARRAY_LENGTH(), PERCENTILE_DISC(), COUNT(), MIN(), MAX(), AVG(), WITH ... AS(), JOIN

Rank and Complexity: SERIES, ARRAY_LENGTH(), AVG(), data type conversion using "::"

If you want to perform the queries on your side, you can find also find the original tables here:

table_bgg_GameItem AS game
table_bgg_Mechanic AS mechanic
