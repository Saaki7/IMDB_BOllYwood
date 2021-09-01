# IMDB_BOllYwood
This repository holds a project dealing with the scraping of data of 3000 Bollywood movies listed in IMDB and involves data pre-processing and EDA of the Data.

## Web Scrapping and [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

I have used bs4 library containing Beautifulsoup in order to collect data from the website of IMDB containing [Bollywoodmovies](https://www.imdb.com/search/title/?title_type=feature&primary_language=hi&sort=num_votes,desc) . Though there are 14000+ movies in the pages, I primarily focused on first 3000 movies which has more data than the others(Old movies with more Null values and less votings and bad ratings).

Beautiful Soup is a Python library for pulling data out of HTML and XML files. It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree. It commonly saves programmers hours or days of work.
With the library beautiful soup, scrapping has been made easier collecting every records of each movie available in the page by creating loops for 3000 movies.


https://www.imdb.com/search/title/?title_type=feature&primary_language=hi&sort=num_votes,desc

This is the link of the first page which contained only 50 movies and carefully observe the link of 2nd page starting 51 and ending with 100 movies.

https://www.imdb.com/search/title/?title_type=feature&primary_language=hi&sort=num_votes,desc&start=51&ref_=adv_nxt

The only difference is that '&start=51&ref_=adv_nxt' part is added in the link..

similarly check the next link starting from 101. https://www.imdb.com/search/title/?title_type=feature&primary_language=hi&sort=num_votes,desc&start=101&ref_=adv_nxt

I observed this is the beauty, since we can construct a for loop for changing one page to another. Check my [web scrapping JupyterNotebook](web_Scrapper-main) for clear knowledge.

## Data Pre-Processing

Me as a novice, I took this data preprocessing part a whole lot of time involving changing types of data for calculations and creating new columns. Data collected from scrapping required more preprocessing to be done. Check my [jupyter_Notebook](Contelligenz_Eda_py.ipynb) on EDA and Preprocessing.


### Bar Chart Showing the number of movies made by top 10 people :relaxed:

![Barchart](/Data/download1.png)



