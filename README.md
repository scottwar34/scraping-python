# web-scraping-in-python
web scraping in python using pandas and beautifulsoup
The first thing we’ll need to do to scrape a web page is to download the page.
We can download pages using the Python requests library.
The requests library will make a GET request to a web server, which will download the HTML contents of a given web page for us.
There are several different types of requests we can make using requests, of which GET is just one.
We can use the BeautifulSoup library to parse this document, and extract the text from the p tag.
We first have to import the library, and create an instance of the BeautifulSoup class to parse our document
