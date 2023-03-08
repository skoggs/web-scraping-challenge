# web-scraping-challenge
A demo of scraping both text and tables from specific websites.

Using both BeautifulSoup and Splinter, Part 1 of this project grabs the contents of a website's HTML and outputs it in an easily referenced title-to-summary dictionary. While it is tooled for this specific website, it can be easily adapted for websites with similar HTML formatting or for different HTML elements. 

Part 2, meanwhile, pulls a table from an HTML and transforms it into a DataFrame. For practice's sake, we forego the use of Panda's handy read_HTML function and use loc functions alongside lists and dictionaries to construct the DataFrame. Some sample data calls and graphs are also included to show off basic functionality of the DataFrame.
