# Web-Scrapping-using-Python
### About
This project provides a Python-based web scraping tool that allows us to extract data from the website "Quotes to Scrape". From this website, scrapping Name, Quotes and the Tags. The data of these three features would be transformed into a structured or tabular form after being extracted from the website and save the data either in the CSV or Excel file.
### Introduction
Web scraping has become an essential technique for extracting valuable data from websites. It is the process of extracting and parsing data in an automated fashion using a computer program. It allows us to automate the process of collecting data for creating datasets from multiple web pages, saving time and effort. With Python's powerful libraries such as BeautifulSoup and requests, web scraping becomes accessible to developers for parsing HTML and extracting information, making it easier to navigate and extract data from web pages. Also using the Pandas Library for Scrapped data into a DataFrame.
### For Scrapping, using the website given below
http://quotes.toscrape.com/page/1/
### Prerequisites
Before begin, ensure that we have the following prerequisites:
* Jupyter Notebook, VS Code or Google Colab
* Excel
### Step-by-Step Guide to Extract Data from a Website using Web Scraping
##### Step 1: Inspect the Website 
Open the website 'http://quotes.toscrape.com/page/1/' to scrape in web browser. Right-click on the webpage and select "Inspect" or "Inspect Element" (the exact wording may vary depending on the browser). This will open the browser's developer tools, allowing us to view the HTML structure of the webpage.

![image](https://github.com/shaheeneqbal/Web-Scrapping-using-Python/assets/67499556/dd795993-6b7a-469f-b15e-7d866e74d7c7)
##### Step 2: Identify the Data
In the developer tools, explore the HTML structure and locate the data which have to extract. Here, I am scrapping author's names, quotes and tags present on the webpage. Take note of the HTML tags, classes, or attributes that wrap the data.

![image](https://github.com/shaheeneqbal/Web-Scrapping-using-Python/assets/67499556/a04fe8f1-6d16-4a6f-b58a-5006a65cf850)
##### Step 3: Choose a Web Scraping Library
Select a suitable web scraping library for Python. Some popular choices include BeautifulSoup, Scrapy, or Selenium. For this guide, I'll use BeautifulSoup, which is known for its simplicity and ease of use.
##### Step 4: Install the Libraries
Install BeautifulSoup, Request and Pandas by running the following command in your terminal or command prompt.
* pip install pandas

* pip install request

* pip install bs4

##### Step 5: Import the Libraries
In Jupyter Notebook, import the libraries shown below:
![image](https://github.com/shaheeneqbal/Web-Scrapping-using-Python/assets/67499556/43d5c228-60b8-4107-bddb-58556a4d80eb)
##### Step 6: Fetch the Webpage
Use the 'requests' library to fetch the HTML content of the webpage. Send an HTTP GET request to the URL of the webpage and store the response.
##### Step 7: Create a BeautifulSoup Object
Creating a BeautifulSoup object by passing the HTML content and the parser library ('html.parser').
##### Step 8: Extract the Data
Use BeautifulSoup's methods to extract the desired data from the HTML. Use methods like '.find()', '.find_all()'. 
##### Step 9: Store the Data
Once we have extracted the data, convert it to a structured format (e.g., CSV, JSON), or store it in a database for later use.
![image](https://github.com/shaheeneqbal/Web-Scrapping-using-Python/assets/67499556/a3293743-954a-43ba-a701-89b791a4351d)
##### Note: when scraping the websites, be respectful and follow the website's terms of service. Avoid overwhelming the website's servers with too many requests or scraping sensitive or personal data without proper consent.
### License
This project is licensed under the MIT License. Feel free to modify and use it as per your requirements.
### Conclusion
Web scraping using Python opens up a world of possibilities for automating data extraction and analysis. Whether a beginner or an experienced developer, this repository provides the tools and resources need to dive into web scraping and harness the power of Python. Enjoy exploring the scripts, honing skills, and unlocking the vast potential of web scraping.

