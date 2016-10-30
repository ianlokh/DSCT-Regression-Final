# DSCT-Regression-Final

##Data Description

This data set is collated from IMDb.com which is currently the world’s #1 most popular and authoritative source for movie, TV and celebrity content. The data that you will be seeing will comprise of information related to 5043 movies such as the actors’ names, number of faces that were present in the movie posters, ratings and etc. This data has been collated originally to find out if there is any better way which we will be able to tell the greatness of a movie without relying on online critics or our own gut feelings. 

In this assignment, we are interested in finding out if there is a better way to determine a movie’s gross earnings (in USD) so that potential investors and sponsors will be able to choose which movie(s) to invest their money in wisely. 

We will be looking at ONLY variables which contains numeric data as well as genres, countries and languages to perform regression modelling and identify which features of a movie contribute to the gross earnings of the movie the most.

There are in total 26 genres present in the data as follow:
- Action
- Adventure
- Animation
- Biography
- Comedy
- Crime
- Documentary
- Drama
- Family
- Fantasy
- Film-Noir
- Game-Show
- History
- Horror
- Music
- Musical
- Mystery
- Romance
- Sci-Fi
- Thriller
- Western
- Sport
- War
- Short
- News
- Reality-TV



The codebook “IMDb-Codebook.pdf” will provide an explanation on variables and the description of the values.

You will need to read in the CSV file in R and then work on the relevant variables as described above.

Questions

We would like to identify which features of a movie contribute to the gross earnings of the movie the most identify which features of a movie contribute to the gross earnings of the movie the most.

1)	Plot a diagram and explain what can you understand about the gross earnings of the movies in this data set from your diagram.

2)	Perform data cleaning and transformation wherever required. (Hint: You may need to make use of log transformation.)

3)	Transform genres, countries and movie languages into dichotomous variables.

4)	Formulate a suitable regression model for the scenario

5)	Compute the coefficient of determination for the regression model. Comment on the adequacy of the model.

6)	Construct a 95% confidence interval on movie duration based on the regression model you have built. Comment on this confidence interval.

7)	Is the regression model that you have built in the previous question significant and why?

8)	Step through your model and determine if there is any multicollinearity in the predictors and adjust your model accordingly.

9)	What is the expected gross earnings of a movie which has the following attributes?
a.	1467,285 users voted for the movie
b.	Action Adventure genre
c.	Originates from USA
d.	Movie duration is 109 minutes
e.	750 reviews from critics
f.	980 reviews from users

10)	 Suppose a sequel was produced as the movie was well received by   many viewers. What is the expected gross earnings of the sequel which has the following attributes?
a.	2,689,764 users voted for the movie
b.	50% increase in movie production budget as compared to the prequel
c.	Action Adventure genre
d.	Originates from USA
e.	60% more likes on the movie's official Facebook page
f.	30% more likes on Actor 1's Facebook page
g.	18% more likes on Actor 2's Facebook page
h.	Movie duration is 125 minutes
i.	913 reviews from critics
j.	5,060 reviews from users



