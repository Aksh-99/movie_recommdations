# Netflix Dataset SQL Project

## About the Dataset

Netflix is a popular streaming service that offers a vast catalog of movies, TV shows, and original contents.  The data consist of contents added to Netflix from 2008 to 2021. The oldest content is as old as 1925 and the newest as 2021. This dataset will be cleaned with PostgreSQL and visualized with Tableau. The purpose of this dataset is to test my data cleaning and visualization skills. The cleaned data can be found below and the Tableau dashboard can be found [here]([link_to_tableau_dashboard](https://prod-uk-a.online.tableau.com/#/site/aksharagopakumar/workbooks/535149?:origin=card_share_link)).

## Data Cleaning

In this project, we will:

1. Treat the Nulls
2. Treat the duplicates
3. Populate missing rows
4. Drop unneeded columns
5. Split columns

Extra steps and more explanation on the process will be explained through the code comments.

## Data Visualization

After cleaning, the dataset is set for some analysis and visualization with Tableau.

**Note**: In the visualization captions, "Contents" means Movies and TV shows, and "Content" may either mean Movie or TV Show.

### Sheet 1. Content Type in Percentage

This first sheet shows the two categories of content in the dataset: Movie and TV show.

- Movies take up 69.9% of the content.
- More details are in the tooltip which shows the exact count of Movie and TV show.

### Sheet 2. Movie & TV Show by Country

This sheet shows the total amount of Movies and TV shows per country from 2008 - 2021.

- The size of the coloured circle on the map indicates the total amount of content.
- The United States of America has the largest size, followed by India and the United Kingdom.
- The Tableau dashboard has a filter for the years 2008 to 2021.

### Sheet 3. Number of Contents Added Through the Years

This time series chart shows the total number of contents added to Netflix from 2008 - 2021.

- Most movies and TV shows were added in 2019.
- The Tableau sheet has a filter for each month of the year.

### Sheet 4. Top Directors

This chart shows the top 10 directors with the most content on Netflix.

- Most of these directors' content are movies.
- Raul Campos and Jan Suter often work together and have directed 18 movies on Netflix.

### Sheet 5. Top Genres

This chart shows the genres with the highest numbers on Netflix.

- Drama & International movies followed by Documentary have the highest number of contents.

### Sheet 6. Top Ratings

This chart shows the top ratings on Netflix.

- Most contents are rated TV-MA, which signifies content for mature audiences in the United States.

### Sheet 7. Oldest Contents on Netflix by Content Release Year

This table shows the 10 oldest movies and TV shows on Netflix.

- The oldest content is from 1925.

### Sheet 8. Content Types Over the Years

This line chart compares the Movie and TV show content added to Netflix over the years.

- More movies have always been added.
- In 2013, the number of movies and TV shows added was almost the same.
- In the first 5 years, only movies were added to Netflix.

### Sheet 9. Release Years with Highest Contents

This chart shows the production years of Movies and TV shows with the highest content on Netflix.

- From 2012 to 2018, Netflix added the most recent content.
- The drop in 2019 may be due to COVID-19, but further analysis is needed.

