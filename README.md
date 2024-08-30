# Investigating-Netflix-Movies
Investigating Netflix Movies By Answering Questions

# Introduction

Netflix! What started in 1997 as a DVD rental service has since exploded into one of the largest entertainment and media companies.Given the large number of movies and series available on the platform, perform exploratory data analysis to better understand this awesome movie decade by providing answers and tasks to the following questions .

# Data
netflix_data.csv
Column	Description
show_id	The ID of the show
type	Type of show
title	Title of the show
director	Director of the show
cast	Cast of the show
country	Country of origin
date_added	Date added to Netflix
release_year	Year of Netflix release
duration	Duration of the show in minutes
description	Description of the show
genre	Show genre


# Techniques To Use In This Project
	• Matplotlib Customization
	• Filtering DataFrames
	• For Loops
	
# Programming Language
	• Python

# Project Step
	• Importing Pandas & Matplotlib
	• Read the Netflix dataset(CSV) to a DataFrame
	• Subset the DataFrame for type "Movie"
	• Filter the to keep only movies released in the 1990s
	• Visualize the duration column of your filtered data to see the distribution of movie durations
	• Filter the data again to keep only the Action movies
	• Count the value of action movies duration lessthan 90 minutes
	•  Another method to find the number of short action movies
		○ Use a for loop and a counter to count how many short action movies there were in the 1990s 
	
# Business Questions
Explore Netflix movie data and perform exploratory data analysis for a production company to uncover insights about movies from a particular decade.

	• What was the most frequent movie duration in the 1990s? Save an approximate answer as an integer called duration.
	• A movie is considered short if it is less than 90 minutes. Count the number of short action movies released in the 1990s and save this integer as short_movie_count.


#Conclusion

In this exploratory data analysis of Netflix movies from the 1990s, we sought to uncover key insights into the characteristics and trends of movies from this decade.

Most Frequent Movie Duration: Through visualizing the distribution of movie durations, we found that the most frequent movie duration in the 1990s was approximately 100 minutes. This suggests that, on average, movies from this era had a standard runtime around this length, reflecting a common industry practice during that time.

Short Action Movies: We also investigated the prevalence of short action movies, defined as those with a duration of less than 90 minutes. Our analysis revealed that there were 7 short action movies released in the 1990s. This count highlights that while the majority of action films from this period adhered to longer runtimes, a notable subset opted for shorter formats.
