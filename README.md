# Recommender-System-with-Web-scraped-data
I made a content-based recommender system and the data that I used for it was obtained by web-scraping that I did myself. 

In this project, I made a webscraper using Python and BeautifulSoup4 library. Using this webscraper, I scraped the website of IMDb to get iitle of the movie, the director, the genre, the actors and the plot. I made three databases of specific genres: Comedy, Mystery and Romance.

Then I made the recommender model in which I cleaned the data to make a "bag of words" for each movie. Similarity was established using cosine similarity and finally the model could predict as many similar movies as wanted. 
