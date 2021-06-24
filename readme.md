Introduction to the Project :

This project is made for automatic web scraping to make scraping easy. It gets a url or the html content of a web page and a list of sample data which we want to scrape from that page. This data can be text, url or any html tag value of that page.

Limitation of this project:

Since the source code of a particular website is different for different types of web pages, scraping simulates human web surfing.
This project works on this URL: https://books.toscrape.com/index.html only.

Working:

The logic wriiten in this repo will take the data from the site and will store the data in a .csv file.

Result:

We were able to scrape the list of all the [names ,price ,link and stock availability] of all the books of the site.
We stored the the output in all_books.csv
It took some 14 odd minutes to scrape all the 1000 books from the Web,

HOW TO RUN:

- Make sure you have the following dependecies in your local machine:-
  1. pandas
  2. BeautifulSoup
  3. requests
- To run the project open driver.ipynb
- Modify the data points you want to extract.
- Run all the cells and a csv file will be created as soon as the code is executed.

FOR DEVELOPERS:

-I have added an addition file named "toolsWhichHelpedBuildTheProject.ipynb"
-This file contains the programming paradims and tools which were used to build the game.
