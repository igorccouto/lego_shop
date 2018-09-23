# Lego Shop Web Scraping

This is a [Scrapy Web Crawling Framework](https://scrapy.org/) project to gather information about products on [Lego Shop](https://shop.lego.com/en-US).

The code starts in http://shop.lego.com/en-US/Themes/ page and crawls among categories of Lego. 

# How to use

You will need Python 3.x to run the scripts.
Python can be downloaded [here](https://www.python.org/downloads/).

You have to install ***scrapy*** framework:
* In command prompt/Terminal: *pip install scrapy*
* If you are using [Anaconda Python distribution](https://anaconda.org/anaconda/python): *conda install -c conda-forge scrapy*

Once you have installed *scrapy* framework, just clone/download this project, access the folder in command prompt/Terminal and run the following command:

*scrapy crawl lego_products -o lego_products.csv*

You can change the output format to JSON or XML by change the output file extension (ex: *products.json*).
