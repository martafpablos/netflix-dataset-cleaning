# Netflix Data Analysis and Cleaning
This project aims to clean and transform a Netflix dataset, containing information about movies and TV shows. The original file includes raw data on titles, directors, countries, release dates, among others. The process includes data cleaning, transformation of data types, and correction of inconsistencies.

## Project Description
The project includes the following stages:

1. **Dataset Loading**: The CSV file with Netflix data is loaded.
2. **Data Exploration**: The first rows of the dataset are explored, and basic statistics are obtained.
3. **Data Type Transformation**: Some columns are converted to more appropriate types, such as dates and categories.
4. **Handling Duplicates and Null Values**: Duplicates and null values are checked and removed.
5. **Cleaning the 'duration' Column**: The duration of movies and TV shows is split into two new columns: movie_duration for movies and num_seasons for TV shows.
6. **Replacing Incorrect Values**: Values like 'Not Given' in the director column are replaced with 'Unknown'.
7. **Generating a New 'main_genre' Column**: The first genre is extracted from the listed_in column for easier classification.
8. **Exporting the Cleaned Dataset**: The cleaned file is saved in a new CSV called netflix_cleaned.csv.
