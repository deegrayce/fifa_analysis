# FIFA Player Performance Analysis
## Overview
Welcome to the FIFA Player Performance Analysis project! In this project, we delved into a dataset containing information about FIFA players, exploring their attributes and conducting some insightful analyses. The primary goal was to gain a better understanding of player demographics, performance, and the relationship between age and overall rating.

## Getting Started
To begin, we imported the powerful pandas library in Python to handle and manipulate our dataset. The data was loaded into a pandas DataFrame named 'df' from a CSV file containing FIFA player information.

## Initial Exploration
We started by taking a quick glance at the first few rows of the dataset using the head() function. Subsequently, we set the "Name" column as the index for easier referencing throughout the analysis.

## Sorting and Filtering
A key aspect of our exploration was sorting the dataset based on player age. We initially sorted the DataFrame in ascending order of age and later explored the oldest players by sorting in descending order.

We identified players older than 30 and went a step further to isolate high-performing veterans, defined as those with an overall rating exceeding 90.

## Feature Engineering
A new column, "Rating per age," was created to examine the relationship between player age and overall performance. However, after some exploration, we decided to drop this column, realizing it wasn't a crucial component for our subsequent analyses.

## Statistical Insights
We computed the mean performance based on age, providing an overview of how player performance tends to change with age. Additionally, we investigated the average age by nationality, shedding light on the age distribution across different countries.

## Conclusion
In conclusion, this FIFA Player Performance Analysis project allowed us to uncover intriguing patterns and insights within the dataset. From exploring the age distribution of players to identifying high-performing veterans, we gained valuable information that can be further analyzed or used for strategic decision-making in various contexts.

Feel free to explore the Jupyter Notebook for a detailed walkthrough of the analysis and the code implemented in this project. Happy exploring!
