# Web-Scraping and Data Analysis Project


Full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.
As you work on this project, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.
 This new project consists of two technical deliverables:
•	Deliverable 1: Scrape titles and preview text from Mars news articles.
•	Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.
## Part 1: Scrape Titles and Preview Text from Mars News

Open the Jupyter Notebook. You will work in this code as you follow the steps below to scrape the Mars News website.
1.	Use automated browsing to visit the [Mars news siteLinks](https://github.com/user/repo/blob/branch/other_file.md). Inspect the page to identify which elements to scrape.
2.	Create a Beautiful Soup object and use it to extract text elements from the website.
3.	Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
   
 1.	Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. An example is the following:
   o	Store all the dictionaries in a Python list.
   o	Print the list in your notebook

## Part 2: Scrape and Analyze Mars Weather Data

Open the Jupyter Notebook folder. You will work in this code as you follow the steps below to scrape and analyze Mars weather data.
1.	Use automated browsing to visit the [Mars Temperature Data SiteLinks](https://github.com/user/repo/blob/branch/other_file.md). Inspect the page to identify which elements to scrape. 

2.	Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
   
3.	Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:
   
 1.	id: the identification number of a single transmission from the Curiosity rover
    
 3.	terrestrial_date: the date on Earth
    
 4.	sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
    
 5.	ls: the solar longitude
    
 6.	month: the Martian month
     
 7.	min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
     
 8.	pressure: The atmospheric pressure at Curiosity's location
     
4.	Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
5.	Analyze your dataset by using Pandas functions to answer the following questions:
   
  a.	How many months exist on Mars?
  b.	How many Martian (and not Earth) days worth of data exist in the scraped dataset?
  c.	What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    1.	Find the average minimum daily temperature for all of the months.
    2.	Plot the results as a bar chart.
4.	Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
  1.	Find the average daily atmospheric pressure of all the months.
  2.	Plot the results as a bar chart.
5.	About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
  1.	Consider how many days elapse on Earth in the time that Mars circles the Sun once.
  2.	Visually estimate the result by plotting the daily minimum temperature.
6.	Export the DataFrame to a CSV file.


 

 

