# Understading the used Analysis Method

Here's a drill-through of what's the method I'm going to use to analyze the following dataset. I'm also using a 4.0 version from GPT to help me understand and do a fully direct analysis.. 

## Headers from IMDB DataSet

### [IMDB Dataset Link](https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows?resource=download)

* Poster_Link - Link of the poster that imdb using
* Series_Title = Name of the movie
* Released_Year - Year at which that movie released
* Certificate - Certificate earned by that movie
* Runtime - Total runtime of the movie
* Genre - Genre of the movie
* IMDB_Rating - Rating of the movie at IMDB site
* Overview - mini story/ summary
* Meta_score - Score earned by the movie
* Director - Name of the Director
* Star1,Star2,Star3,Star4 - Name of the Stars
* No_of_votes - Total number of votes
* Gross - Money earned by that movie

## Analisys Method

### Descriptive Statistics:

- [ ] Calculate mean, median, standard deviation, minimum, and maximum for numerical columns like IMDB_Rating, Meta_score, No_of_Votes, and Gross.
- [ ] For categorical columns like Certificate, Genre, and Director, determine the frequency of each category.


### Visualizations:

- [ ] Histograms for IMDB_Rating, Meta_score, No_of_Votes, and Gross to understand the distribution.
- [ ] Box plots for IMDB_Rating and Meta_score to identify outliers and understand spread.
- [ ] Bar charts for most frequent categories in Certificate, Genre, and Director.
- [ ] Scatter plot between IMDB_Rating and Meta_score to see if there's any correlation between the two scores.

### Temporal Analysis:

- [ ] Analyze the trend of ratings (IMDB_Rating and Meta_score) over the years (Released_Year).

### Genre Analysis:

- [ ] Determine which genres have the highest and lowest average ratings.
- [ ] See if certain genres tend to have more votes or higher gross earnings.

### Directors and Actors Analysis:

- [ ] Identify the most frequent directors and actors in the dataset.
- [ ] Determine which directors and actors are associated with the highest and lowest ratings.

### Correlations:

- [ ] Check for correlation between numerical columns like IMDB_Rating, Meta_score, No_of_Votes, and Gross.
- [ ] Text Analysis (if applicable):

### Outlier Identification:
- [ ] Use descriptive statistics and visualizations to identify and investigate outliers, especially in columns like IMDB_Rating, Meta_score, and Gross.
