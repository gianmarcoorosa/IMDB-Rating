This repository contains a project on IMDB movie ratings that I completed with 3 other students 
for the course Statistical Methods for High Dimensional Data.

In this project, we used the bulk datasets available on the IMDB website. We also added some 
information to the dataset using Wikidata.

In the final dataset, each row represents a movie, and most columns indicate the presence or 
absence of specific actors/writers/composers in the movie. The design matrix is very sparse 
given the structure of the dataset.

We implemented several models including ridge, lasso, SCAD, MCP, grouped lasso, trees, random 
forest and XGBoost, evaluating their performance based on MSE and interpretability.

In the final part, we scraped the cast of a specific movie that will be released in the future 
and predicted its rating using XGBoost.
