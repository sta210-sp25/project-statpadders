# Data

If using an external dataset (that doesn't come in an R package), place data file(s) in this folder.

Then, include metadata about your dataset including information on provenance, data dictionary, etc.

The data dictionary for your data file(s) using the following format.

## imdb_top1000.csv

| Variable  | Description               |
|:----------|:--------------------------|
| IMDB_Rating | Rating of the movie at IMDB site, out of 10 points |
| IMDB_scaled^* | Rating of the movie at IMDB site, scaled to be out of 100 points, (for comparability to Meta_Score |
| Meta_score | Aggregate critics' score earned by the movie, out of 100 points |
| Series_Title | Name of the movie |
| Director | Name of the Director |
| Overview | Mini story/summary of title |
| Gross | Gross revenue earned by that movie (in millions of USD)|
| gross_scaled | Gross revenue (in millions of USD); divided by 1,000,000 for readability and consistency (e.g., 20 = $20 million) |
| gross_cent  | Gross revenue (in millions of USD); mean-cntered |
| No_of_votes | Total number of votes  |
| no_votes_scaled | Total number of votes, (in millions); divided by 1,000,000 for readability and consistency (e.g., 10 = 10 million) |
| votes_cent | Total number of votes received on IMDB (in millions); mean-centered for interpretability  |
| Released_Year  | Year at which that movie released |
| decade  | Decade at which that movie released |
| Runtime | String, denoting total runtime of the movie (in minutes) |
| runtime | total runtime of the movie (in minutes), factored as a numeric variable |
| runtime_cent | total runtime of the movie (in minutes), mean-centered for interpretability |
| Certificate | Censorship certificate earned by that movie |
| certificate | Censorship certificate earned by that movie, consolodated into G, PG, PG-13, R and Other for modern interpretability |
| Genre | Genre of the movie |
| difference | Scaled difference between Metascore and IMDB score |
| difference_binary | binary variable 1 if audience score's divergence is +/- 1 SD from the mean, 0 if otherwise |


