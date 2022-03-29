# Mars_Mission
## Purpose
This project scrapes data off of the NASA website and adds the data to an app.

## Execution

* Using BeautifulSoup and Splinter, I scraped, recent news, space facts from Nasa, and  full-resolution images of Mars’s hemispheres and the titles of those images from USGS Astrogeology.
* I used a Flask app trigger the scrape function, update the Mongo database with the results, and return that record of data from the database on my webpage.
* After a Flask is created, and PyMongo establishes a connection to the MongoDB server. This connection is used to run the scrape function located in the imported scraping.py file.
* In my index.html, I added this scrape function as a button a user can press and activate the scraping of the most recent data, right on my website.
* I used bootstrap functions to customize some features and UI on my site. Future improvements will build on design fundamentals.
