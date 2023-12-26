#E-Commerce Product Data Acquisition through Web Scraping

Utilized python's BeautifulSoup library to perform the webscraping on flipkart mobiles under 50k page using the below mentioned url of the page
"https://www.flipkart.com/search?q=mobiles+under+50k&as=on&as-show=on&otracker=AS_Query_HistoryAutoSuggest_1_13_na_na_na&otracker1=AS_Query_HistoryAutoSuggest_1_13_na_na_na&as-pos=1&as-type=HISTORY&suggestionId=mobiles+under+50k&requestId=970c95e8-6a4b-4087-a4e1-6aa5090bdd2c&as-searchtext=mobiles+under&page=".

The important libraries used in this project are BeautifulSoup, Requests, Pandas and html5lib. Next, accessing the html content from webpage to test whether the page has permission to extract html data by sending a request to it through the requests library. We have access if the status code is 200; otherwise, we do not have access. After that, to parsing the html content we had used the html5lib library. Then next using the html elements collect the product name, prices, description and reviews and save them in a list. Atlast, created a csv file and save the information in it. On performing the web scraping and converted the data into csv file, it makes a reduction in data collection time and facilitating real time data analysis and decision making.
