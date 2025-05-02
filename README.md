Analysis of Divergence Between Audience and Critic Scores
From Top 1000 IMDB Films 1950 - 2019

Statpadders: Camden Reeves, Toma Shigaki-Than, CJ Frederickson

Data dictionary

The data dictionary can be found here. Among the dataset, we will use the following listed below:

Response variables:

IMDB_scaled - Rating of the movie at IMDB site, scaled to match meta-score

Meta_score - Score earned by the movie 

difference - Difference from which the IMDB score diverges from the MetaScore

difference_binary - binary variable of differecne which takes on values 1 and 0

 **1 (divergent):** if the difference was less than -13 or greater than 9, corresponding approximately to films with audience-critic score differences exceeding ±1 standard deviation from the mean.

**0 (non-divergent):** otherwise.

Identifiers:

Series_Title = Name of the movie

Director - Name of the Director

Overview - Mini story/summary of title

Predictor Variables - Numerical:

Gross - Money earned by that movie

No_of_votes - Total number of votes 

Released_Year - Year at which that movie released

Runtime - Total runtime of the movie

Predictor Variables - Categorical:

Certificate - Certificate earned by that movie 

Genre - Genre of the movie
