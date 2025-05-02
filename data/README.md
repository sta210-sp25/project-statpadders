# Data

If using an external dataset (that doesn't come in an R package), place data file(s) in this folder.

Then, include metadata about your dataset including information on provenance, data dictionary, etc.

The data dictionary for your data file(s) using the following format.

## imdb_top1000.csv

| Variable  | Description               |
|:----------|:--------------------------|
| IMDB_Rating | Rating of the movie at IMDB site |
| IMDB_scaled | Rating of the movie at IMDB site, scaled to be out of 100 points |
| Meta_score | Score earned by the movie, out of 100 points |
| Series_Title | Name of the movie |
| Director | Name of the Director |
| Overview | Mini story/summary of title |
| Gross | Gross rebvenue earned by that movie |
| gross_scaled | Gross revenue (in millions of USD); original values divided by 1,000,000 for readability and consistency (e.g., 20 = $20 million) |
| No_of_votes | Total number of votes  |
| No_votes_scaled | Total number of votes, scaled in millions  |
| Released_Year  | Year at which that movie released |

| Runtime | Total runtime of the movie |
| Certificate | Certificate earned by that movie |
| Genre | Genre of the movie |
| Difference | Scaled difference between Metascore and IMDB score |
| Difference_binary | binary variable 1 if audience score's divergence is +/- 1 SD from the mean, 0 if otherwise |


