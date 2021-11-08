---
title: Rights
nav: true
---
# Rights, permissions, licences

-----

### research data ethics

{% include figure.html img="Oxxx.png" alt="Title" caption="Title" width="75%" %}

When working with data it is vitally important that you have the right ethical permissions and clearances, this is true even when working with publically available datasets. This is particularly important if you plan on webscraping pages for data. Before undertaking reserach on exisitng datasets, be sure to read the terms and conditions of the use of the data, contact Griffith research ethics <a href='https://www.griffith.edu.au/research/research-services/research-ethics-integrity' target="_blank"> here <a/>  


## Gathering data from repositories
  
  
## Gathering data VIA API
### What is an API? (Application Programming Interface)
API is the acronym for Application Programming Interface, which is a software tool that allows two applications to talk to each other. In the case of collecting web data, this is a database that stores the webpages data and something that can read, display or store that data (i.e. a webbrowser, a programming language such as python or some other program on your computer, or a cloud based application).

If a website has an API, then use it. Generally, it won't let us collect data that your not allowed to collect, and its by far the easiest way to collect a websites data.

Check here for (by no means comprehensive) lists of websites with API access:

<a href='https://apilist.fun/' target='_blank'>API list</a>

<a href='https://github.com/public-apis/public-apis' target='_blank'>Public APIs</a>

Guardian.co.uk <a href='https://open-platform.theguardian.com/' target='_blank'>API</a>

Australian news sources <a href='https://mediastack.com/sources/australia-news-api' target='_blank'>API</a> 

## How do we use an API

You use URL's to collect a websites data with an API, this is refered to as an `API request`. There will be certain sections of the API request that can be manipulated to collect specific data. You will need to check out the websites API documentation for details.

Once you have a formulated a suitable API request, you will need to pull the data (i.e. get it onto your computer). This is most commonly achieved using a programming language. We generally use  R or Python.  If you are comfortable with either of these languages check these guides.

<a href='https://cran.r-project.org/web/packages/httr/vignettes/api-packages.html' target='_blank'> r-project</a>

<a href='https://www.dataquest.io/blog/python-api-tutorial/' target='_blank'> Python API Tutorial </a>

Some commonly used websites, such as Twitter, have packages that can be used to interact with the API. Packages that use Twitter API's:

R: rtweet 

python: Tweepy

## Web Scraping
Web scraping the process of scraping webpages for data points and creating a dataset that is usable for analysis. 
While web scraping can be done manually by a software user, the term typically refers to automated processes implemented using a bot or web crawler. 

"Data displayed by websites can only be viewed using a web browser. Most websites do not allow you to save a copy of this data 
to a storage location or database. If you need the data, the only option is to manually copy and paste the data
- a very tedious job which can take many hours or days to complete. Web Scraping is the technique of automating this process,
so that instead of manually copying the data from websites, the Web Scraping software will perform the same 
task within a fraction of the time." 
<a href='https://www.webharvy.com/articles/what-is-web-scraping.html' target="_blank">www.webharvy.com/articles/what-is-web-scraping.html</a>.

Web Scraping is different to Web Crawling in that web scraping is for specific data points and web crawling is to index whole pages. 

A web scraping software will automatically load, crawl and extract data from multiple pages of websites based on your requirement. It is either custom built for a specific website or one which can be configured to work with any website  

There are two basic categories of webscraping software,  the first category are browsers or cloud based and installed locally to you computer. This is your webscraper IO type tool and can pull data from individual webapages. 
  
The second method is to use code to extract the data requried. There are a variety of packages used in Python and R that will scrape data eg; Beautiful soup, selinium, scrapy.

## Data copyright





{% include button.md text="bla bla bla" link="https://vimeo.com/......." color="info" %}

-----

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/2-why.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/4-build.html">NEXT --></a>
</p>
