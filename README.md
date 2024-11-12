# Netflix Data Analysis and Visualization
This project is a comprehensive analysis of Netflix's movie and TV show catalog, focused on understanding the types of content offered, trends in content additions, and various metrics related to genre, country, duration, and ratings. The notebook netflix_visualization.ipynb contains the code and visualizations used in this analysis, making it suitable for a data portfolio showcase.

Overview

Data Cleaning: Handling missing values, converting data types.
Data Analysis and Visualization: Creating visualizations to gain insights into Netflix’s content catalog

Dataset

The dataset used in this analysis is publicly available on Kaggle: Netflix Shows Dataset.

License: CC0: Public Domain – This dataset is in the public domain, meaning it is free to use for any purpose.

Description: This dataset contains information on movies and TV shows available on Netflix, including columns such as title, director, cast, country, date_added, release_year, rating, duration, listed_in (genres), and description.

Data Cleaning Steps

The data was initially cleaned in Excel, including tasks such as trimming whitespace. In Python, further cleaning was performed using the following steps:

Handling Missing Values: Replaced missing values in director, cast, country, and rating columns with "Unknown" to retain as much data as possible.

Data Type Conversion: Converted date_added to datetime format and extracted year_added and month_added for time-based analysis.

Standardization: Standardized text columns (e.g., country names and rating values) to ensure consistency.

Extracting Duration: Converted duration to numeric format (e.g., duration_minutes) for movies, with season counts handled separately for TV shows.

Genre Splitting: Split multi-genre entries in the listed_in column for individual genre analysis.

Visualizations

Content Type Distribution: A pie chart showing the distribution of Movies vs. TV Shows.

Content Addition Trends Over Time: A line chart illustrating the trend of content added over the years.

Top Genres: A bar chart or treemap showing the most common genres available on Netflix.

Content by Country: A bar chart displaying the top 10 countries with the most content.

Ratings Distribution: A bar chart showing the distribution of maturity ratings (e.g., PG, TV-MA).

Duration Analysis:

Movies: A histogram showing the distribution of movie durations.

TV Shows: A histogram showing the distribution of season counts.

Project Goals

The proportion of movies versus TV shows.
Trends in Netflix’s content addition over time.
Most popular genres, countries, and maturity ratings.
Distribution of content duration for both movies and TV shows.
Top actors and directors contributing to Netflix’s offerings.
How to Run the Notebook

Future Work

Deep Dive into Genre Trends Over Time: Analyzing how genre preferences have evolved.
Sentiment Analysis on Descriptions: Gaining insights into the tone and theme of Netflix’s content.
Acknowledgments

Dataset: Netflix Shows Dataset on Kaggle by Shivam Bansal
License: CC0: Public Domain
