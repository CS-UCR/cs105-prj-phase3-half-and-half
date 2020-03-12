To begin, we scraped data on the top 1000 movies from https://www.imdb.com/search/title/?count=100&groups=top_1000&sort=user_rating.
The data includes information such as IMDB rating, title, runtime, genre, number of votes, metascore, gross income, and intended audience rating. 

The first scatterplot shows the relationship between IMDB rating and runtime. The second scatterplot shows the relationship between metascore and runtime. There are some outliers, but most movies tend to be within 100 to 200 minutes long.

Out first line graph shows content rating vs IMDB score, and the second rating shows content rating vs metascore. 

To follow, we represented our data through histograms. The first histogram shows the frequency of metascores (skewed to the left) and the second histogram shows the frequency of IMDB ratings (skewed heavily to the right).

We then created linear regression models to determine whether metascore and runtime as well as IMDB rating and runtime have a correlation. Through this, we determined that metascore and runtime have a slightly negative correlation, while IMDB rating and runtime have no correlation.

Contributions: For Phase 1: Moses, Justin, and Thomas found imdb datasets and contributed to the web-scraper. Justin created the initial web-scraper design, Moses extended it to work on multiple pages, and Thomas tested the web-scraper. For Phase 2 and 3, we all met up and created the EDA for our project. Moses created the scatterplot and line graph, Thomas created the bar graphs, and Justin created the linear regression graphs.


Before running the notebook, make sure the csv dataset is in the same directory as the notebook. There are no extra dependencies used in our project.



UPDATE 


“TODO - add a detailed readme / report to the repo. Be sure to include a description of the project, contributions of each team member. And then incorporate additional analysis looking at gross rate and other features”
