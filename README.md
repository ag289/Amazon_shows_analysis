# Amazon Shows Data Analysis
Analysis of Amazon Prime Shows and Movies

## Research Questions

### Question 1 - What is the distribution of movie versus TV show titles?

![Bar Graph of Movies vs TV Shows](https://github.com/ag289/Amazon_shows_analysis/blob/main/Q1.PNG)

Based on the bar plot, it is evident that the number of movies is significantly greater than the number of TV shows. Specifically, there are 50,892 movies and 4,739 TV shows in the dataset.
We can go even further by analyzing a subgroup based on release year.

![Release year Graphc](https://github.com/ag289/Amazon_shows_analysis/blob/main/Q1-2.PNG)

### Question 2 - What are the most common genres and how are they distributed across titles?

![Bar Graph of Common Genres](https://github.com/ag289/Amazon_shows_analysis/blob/main/Q2.PNG)

The bar graph indicates that the drama genre had the most titles, with approximately 20,000, while the war/reality genres had the fewest, with fewer than 1,000 titles. 
This graph also illustrates that the drama genre is the most popular genre, as no other genre has even half as many titles as the drama genre.

### Question 3 - Are there any correlations between IMDb and TMDB scores?

![Scatterplot to Calculate correlation](https://github.com/ag289/Amazon_shows_analysis/blob/main/Q3.PNG)

 - A correlation coefficient of 0.77 indicates a strong positive correlation between imdb_score and tmdb_score. 
 - This means that as the imdb_score of a title increases, the tmdb_score tends to increase as well. 
 - The scatter plot also shows a positive linear relationship between the two variables, with a mostly linear pattern of points. Overall, this suggests that there is a strong association between imdb_score and tmdb_score, and that they may be measuring similar aspects of the title's quality.
 - However, there is also some variability in the data, with some titles having high scores on both platforms while some have low scores on both.

### Question 4 - Which countries are most frequently involved in the production of these titles?

![Barchart of Titles and Top 10 countries](https://github.com/ag289/Amazon_shows_analysis/blob/main/Q4.PNG)

This bar chart shows the number of titles produced by the top 10 countries. The highest number of titles are produced by the United States, with a count of 34,823. 
This is followed by Great Britain (5,116), Canada (2,838), India (1,950), and France (1,876). 
The remaining five countries in the top 10 include Japan, Germany, Italy, South Korea, and Spain, with production counts ranging from 591 to 1,223.

### Question 5 - What is the distribution of average runtime by genre?

![Barplot showing the average runtime of different genres](https://github.com/ag289/Amazon_shows_analysis/blob/main/Q5.PNG)

The bar plot clearly indicates that the 'history' genre boasts the highest average runtime among all genres, while the 'reality' genre stands at the bottom with the lowest average runtime. 
Interestingly, the drama, music, thriller, war, and romance genres follow closely with relatively similar average runtimes, making them the runner-ups.
