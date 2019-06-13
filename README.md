# MPST-Movie-Plot-Synopses-with-Tags


## 1.1 Sources and Refernces: Data Source : 
https://www.kaggle.com/cryptexcode/mpst-movie-plot-synopses-with-tags#mpst_full_data.csv 

Research paper : https://www.aclweb.org/anthology/L18-1274 (https://www.aclweb.org/anthology/L18-1274) 

Research paper : http://ritual.uh.edu/mpst-2018/ (http://ritual.uh.edu/mpst-2018/)

## 1.2 Business Constraints:

Predict as many tags as possible with high precision and recall. 2. Incorrect tags could impact customer experience. 3. No strict latency constraints.

## Machine Learning Problem: 
Contains all the IMDB id, title, plot synopsis, tags for the movies. 
There are 14,828 movies' data in total. The split column indicates where the data instance resides in the Train/val/Test split. 

Columns: 

imdb_id:- IMDB id of the movie.

title:- Title of the movie.

plot_synopsis:- Plot Synopsis of the movie.

tags:- Tags assigned to the movie. 

split:-Position of the movie in the standard data split. 

synopsis_source:-From where the plot synopsis was collected

## Score:
With all tags: 0.36

With top_5 tags: 0.52

With top_3 tags: 0.54

Achived a better score than what is mentioned in research paper.
