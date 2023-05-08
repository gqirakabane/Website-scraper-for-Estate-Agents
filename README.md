# Website-scraper-for-Estate-Agents
Scrapes data from websites listed in google sheets and stores them by creating a new sheet for each website
This code first opens the worksheet containing the list of websites to scrape, then iterates over each row and extracts the website URL. 
It then attempts to scrape the data from the website using BeautifulSoup and appropriate tags and attributes, and stores the extracted data in variables. 
The code then creates a new worksheet with the website name as the title and adds headers to the worksheet. 
Finally, it adds the scraped data to the new worksheet. 
Any errors encountered during scraping are printed to the console.
