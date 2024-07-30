# Data-Sourcing-Challenge : Module 6 Assignment 
> The task is to prepare some data for a recommendation system to help people find movie reviews and related movie statistics.Data is extracted from > two different sources: The New York Times API and The Movie Database, and merged together.
> The file: retrieve_movie_data.ipynb
> the output is stored as a .csv file called: nytimes_tmdb_collected_data.csv.

> The code has 3 parts:
> This Challenge has three parts, and must be completed in order:

## Part 1: Access the New York Times API:
> This part consists of the use of the NY times API and searches for review headlines with the word 'Love'
> query='love'
> filter_query = 'section_name:("Movies") AND type_of_material:("Review") AND headline:("love")'
> Article Search API limits results to 10 per page so a sleep function is incorporated.
>
## Part 2: Access The Movie Database API:
> This part consists of the use of the TMDB API and searches for movie details. It is a 2 step process
>  The search query is used to find the movie ID from the search by title followed by the movie query to search by the movie id returned by the > > search query
>
## Part 3: Merge and Clean the Data for Export:
> The collected the data from both APIs are merged based on the column 'title'
> the final output is presented in the.csv file that can be exported for future use.

