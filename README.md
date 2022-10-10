# Web-Scraping-with-Python
Web scraping is a data extraction process used to extract data from different websites and store them in a desired file format like csv,excel etc. 
to perform web scraping there are few modules available in the market which can be used for web sraping. 

## Following are the modules used mainly for web scraping : 
* Requests
* Urllib3
* BeautifulSoup
* Selenium
* Scrapy

## Steps to be followed while performing Web Scraping : 

* Step 0 : Setting up the Environment
* Step 1 : Get the HTML
* Step 2 : Parse the HTML
* Step 3 : HTML tree traversal
* Step 4 : Collection of Data, Cleaning the data and using the data

## Details to be observed : 

### Step 0 : Setting up the Environment 
<ol>
  <li> In order to use the power of python to scrap websites, we can use existing libraries to get the job done.
  <li> We will install the following libraries using pip :

``` 
pip install requests
```

```
pip install html5lib
``` 

``` 
pip install requests
```

    
</ol>


### Step 1 : Fetching the HTML content
<ol>
  <li> In order to work with the HTML, we will have to get the HTML as a string.
  <li> We will leverage the power of python requests module to get this done!
  <li> The next step then will be to parse the HTML content and give it a tree like structure so that it can be traversed.
</ol>

### Step 2 : Parse the HTML
<ol> 
  <li> Once the HTML is fetched using the requests as an string, we need to parse it.
  <li> For parsing, we will use python's BeautifulSoup module which will create a tree like structure for our DOM.
</ol>
