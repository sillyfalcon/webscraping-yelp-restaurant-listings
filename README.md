# webscraping-yelp-restaurant-listings
<b>Webscraping Yelp restaurant listings using Requests, BeautifulSoup and Pandas</b>  
Check out the Jupyter notebook here: https://jovian.ai/anushree-k/restaurant-listings-notebook

<b> Problem Statement</b>  
In this notebook we will write python functions that will create a CSV file containing details of restaurants that are listed for the city of New York, USA on www.yelp.com.

    Name: Name of the restaurant
    Cuisine: Type of food
    Stars: Rating based on user inputs for this restaurant
    Reviews: Number of users who rated this restaurant
    Address: Address of the restaurant
    Contact: phone number
    Website: Yelp url for the restaurant
    
<b>Steps we'll follow</b>:

- Identify the webpage to be scraped
- Download the webpage using requests and save it into a HTML file
- Parse the HTML code using BeautifulSoup
- Compile the extracted details into Python lists and dictionaries parse_restaurant()
- Introduce a time delay of 1 second for ethical scraping
- Extract and combine data for multiple pages - for ...loop:
- Write the combined data into a CSV file

The output CSV file contains 7 columns and 240 rows of data from 24 pages of HTML from www.yelp.com
