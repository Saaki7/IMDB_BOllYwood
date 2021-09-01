# IMDB_BOllYwood
This repository holds a project dealing with the scraping of data of 3000 Bollywood movies listed in IMDB and involves data pre-processing and EDA of the Data.

## Web Scrapping and [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

I have used bs4 library containing Beautifulsoup in order to collect data from the website of IMDB containing [Bollywoodmovies](https://www.imdb.com/search/title/?title_type=feature&primary_language=hi&sort=num_votes,desc) . Though there are 14000+ movies in the pages, I primarily focused on first 3000 movies which has more data than the others(Old movies with more Null values and less votings and bad ratings).

Beautiful Soup is a Python library for pulling data out of HTML and XML files. It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree. It commonly saves programmers hours or days of work.
With the library beautiful soup, scrapping has been made easier collecting every records of each movie available in the page by creating loops for 3000 movies.

## Data Pre-Processing

Me as a novice, this data preprocessing part took me a whole lot of time involving changing types of data for calculations and creating new columns. Data collected from scrapping required more preprocessing to be done. You can check my  



