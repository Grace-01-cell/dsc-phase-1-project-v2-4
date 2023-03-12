# Overview
This project analyzes the resource needed by microsoft company before starting the production of movies. Microsoft company should do analysis to the data to make a distinct resolution before starting and investing in production.

---

 #  BUSINESS PROBLEM
 Microsoft sees all of the big companies producing original video content and wants in on the action. They've decided to start a new movie studio, but they know nothing about filmmaking. You are tasked with determining which types of films are currently performing well at the box office. You must then translate your findings into actionable insights that the head of Microsoft's new studio can use to help decide what kinds of films to make.

 ---
 
 # 2.Data Understanding
 The data used was obtained from three renowned movie websites:
 1. Box Office Mojo (https://www.boxofficemojo.com/) - bom.movie_gross.csv

 2. IMDB (https://www.imdb.com/) - im.db

 3. The Numbers (https://www.the-numbers.com/)- tn.movie_budgets.csv
 
 * From the [first dataset](bom.movie_gross.csv) which is in `.csv` format, we have the title, studios, domestic gross revenue, foreign gross revenue and the year in which the movie was released. We will use data from the studio and domestic gross columns for the analysis .
 
* From the [second dataset](im.db) which is in `.db` format, we have a database with 8 tables containing different types of non-monetary information about films such as their directors, writers, and genres, and the ratings and [more](images/imdb_data_erd.jpeg). We will use information from movie basics and movie ratings tables.
 
 
 * From the [first dataset](bom.movie_gross.csv) which is in `.csv` format, we have the title, studios, domestic gross revenue, foreign gross revenue and the year in which the movie was released. We will use data from the studio and domestic gross columns for the analysis .
 
* From the [second dataset](im.db) which is in `.db` format, we have a database with 8 tables containing different types of non-monetary information about films such as their directors, writers, and genres, and the ratings and [more](images/imdb_data_erd.jpeg). We will use information from movie basics and movie ratings tables.
 
 
 * From the [third dataset](data/tn.movie_budgets.csv.gz) which is in `.csv` format, we have the names, release dates, production budget, domestic gross revenue and worldwide gross revenue of films that have been released. Here, we use information from the production budget and worldwide gross columns. We calculate correlation of the two and further calculate return on investment using data from the two.

---

# 3.Method Used
This project used the following;
1. Visualstudio code

2.Statistics

3.Matplotlib

4.Seaborn

5.Numpy

6.Pandas

7.python

---

# 4.Data visualization
we used the following visualizations;
(images/top_10_studios.png)
(images/ROI_per_month.png)
(images/distribution_of_release_films_per_month.png)

---
## Recomendations

 1. Microsoft should consider Partnering with the top-performing studios: it may want to consider partnering with the top-performing studios such as Walt Disney Studios Motion Pictures, Warner Bros. Pictures, or Universal Pictures to leverage their success and increase its own revenue.

 2. The months with the most film releases are August, September, and October. This data can help microsoft studios to plan their release schedules, as they may face increased competition during these months.
The months with the fewest film releases are January, February, and April. These months may provide an opportunity for microsoft to release their films with less competition.

3. we can determine which months have a higher or lower ROI for movie releases movies released during the holiday season have a higher ROI. films released earlier in the year have lower ROI. Overall, this  gives Microsoft useful information for making strategic decisions about when to release their films.