## What is a dynamic website?
### A dynamic website is a type of website that can update or load content after the initial HTML load. So the browser receives basic HTML with JS and then loads content using received Javascript code. Such an approach allows increasing page load speed and prevents reloading the same layout each time you'd like to open a new page.

### Scraping static websites refers to the process of extracting data from web pages that have fixed HTML content. In a static website, the HTML code remains the same each time the page is loaded, and the data you want to scrape is embedded directly in the HTML source code.

## Web Scraping best practices to follow to scrape without getting blocked
### 1- Respect Robots.txt
### Web spiders should ideally follow the robot.txt file for a website while scraping. It has specific rules for good behavior, such as how frequently you can scrape, which pages allow scraping, and which ones you can’t. 
### 2- Do not follow the same crawling pattern
### Web scraping bots tend to have the same crawling pattern because they are programmed that way unless specified. 
### 3- Make requests through Proxies and rotate them as needed
### Multiple requests coming from the same IP will lead you to get blocked, which is why we need to use multiple addresses. When we send requests from a proxy machine, the target website will not know where the original IP is from, making the detection harder.

## What is Playwright, and how does it assist in web scraping tasks? 
### Playwright is an open-source library and automation tool developed by Microsoft. It provides a high-level API for browser automation and allows developers to control and interact with web browsers programmatically. Playwright supports multiple browser engines