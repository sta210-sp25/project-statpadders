# Analysis of Divergence Between Audience and Critic Scores From Top 1000 IMDB Films 1950 - 2019

**Statpadders:** Camden Reeves, Toma Shigaki-Than, CJ Frederickson

# Description
This project analyzes factors contributing to significant differences between critic and audience film ratings. Using logistic regression, it identifies structural features that predict when a film defies critical consensus.


# Data dictionary


| Variable  | Description               |
|:----------|:--------------------------|
| IMDB_Rating | Rating of the movie at IMDB site, out of 10 points |
| IMDB_scaled* | Rating of the movie at IMDB site, scaled to be out of 100 points, (for comparability to Meta_Score |
| Meta_score | Aggregate critics' score earned by the movie, out of 100 points |
| Series_Title | Name of the movie |
| Director | Name of the Director |
| Overview | Mini story/summary of title |
| Gross | Gross revenue earned by that movie (in millions of USD)|
| gross_scaled* | Gross revenue (in millions of USD); divided by 1,000,000 for readability and consistency (e.g., 20 = $20 million) |
| gross_cent*  | Gross revenue (in millions of USD); mean-cntered |
| No_of_votes | Total number of votes  |
| no_votes_scaled* | Total number of votes, (in millions); divided by 1,000,000 for readability and consistency (e.g., 10 = 10 million) |
| votes_cent* | Total number of votes received on IMDB (in millions); mean-centered for interpretability  |
| Released_Year  | Year at which that movie released |
| decade*  | Decade at which that movie released |
| Runtime | String, denoting total runtime of the movie (in minutes) |
| runtime* | total runtime of the movie (in minutes), factored as a numeric variable |
| runtime_cent* | total runtime of the movie (in minutes), mean-centered for interpretability |
| Certificate | Censorship certificate earned by that movie |
| certificate* | Censorship certificate earned by that movie, consolodated into "G", "PG", "PG-13", "R" and "Other" for modern interpretability |
| Genre | Genre of the movie |
| difference* | Scaled difference between Metascore and IMDB score |
| difference_binary* | Binary indicator of score divergence; 1 if the critic–audience score gap exceeds ±1 standard deviation, 0 otherwise |

\* *denotes variable created or mutated from its original state for the purpose of our evaluation*
