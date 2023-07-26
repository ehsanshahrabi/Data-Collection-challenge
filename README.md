# Web Scraping and Data Analysis Project - Marc Edition

## Deliverable 1: Scrape Titles and Preview Text from Mars News

In this part, you will use Splinter and BeautifulSoup to scrape titles and preview text from Mars news articles available on a specific website.

## Deliverable 2: Scrape and Analyze Mars Weather Data

In this part, again use Splinter and BeautifulSoup to scrape Mars weather data from a table on another website. Following the scraping, you will perform data analysis using Pandas to answer specific questions related to the weather on Mars.

## Technical Details

### Deliverable 1: Scrape Titles and Preview Text from Mars News
The code for this deliverable can be found in the 01-part_1_mars_news.ipynb notebook. It uses the splinter library to automate browsing and BeautifulSoup to parse the HTML elements.

The steps involved in this deliverable are as follows:

Visit the Mars news site using splinter.

Create a BeautifulSoup object to parse the HTML.

Extract all the text elements containing news articles using their class attribute.

Loop through the text elements and extract the title and preview text for each article.

Store the extracted data in a list of dictionaries, where each dictionary represents a news article.

### Deliverable 2: Scrape and Analyze Mars Weather Data

The code for this deliverable can be found in the 01-part_2_mars_weather.ipynb notebook. It also uses splinter and BeautifulSoup for web scraping, along with Pandas for data analysis and visualization.

The steps involved in this deliverable are as follows:

Visit the website containing Mars weather data using splinter.

Create a BeautifulSoup object to parse the HTML.

Extract all the rows of data from the table using their class attribute.

Assemble the scraped data into a Pandas DataFrame with appropriate column headings.

Perform data analysis using Pandas functions to answer specific questions about the Mars weather data.

## Analysis Questions

The data analysis in 01-part_2_mars_weather.ipynb answers several key questions about Mars weather data:

How many months exist on Mars? (Answer: 12 months)

![Screenshot 2023-07-26 094823](https://github.com/ehsanshahrabi/Data-Collection-challenge/assets/124327258/65d3ed3b-66ce-4818-94ef-7293a98be7ad)

How many Martian (and not Earth) days worth of data exist in the scraped dataset? (Answer: 1867 Martian days)

What are the coldest and warmest months on Mars (at the location of Curiosity)? (Answer: The third month is the coldest, and the eighth month is the warmest)

![Screenshot 2023-07-26 094906](https://github.com/ehsanshahrabi/Data-Collection-challenge/assets/124327258/6752a75d-c8e5-41f3-af5e-3386135166c1)

Which months have the lowest and highest atmospheric pressure on Mars? (Answer: The sixth month has the lowest pressure, and the ninth month has the highest pressure)

![Screenshot 2023-07-26 094930](https://github.com/ehsanshahrabi/Data-Collection-challenge/assets/124327258/6d082ea3-c651-44c0-acf4-2d516153109d)

About how many terrestrial (Earth) days exist in a Martian year? (Answer: Roughly 675 days, equivalent to 687 Earth days)

![Screenshot 2023-07-26 094944](https://github.com/ehsanshahrabi/Data-Collection-challenge/assets/124327258/3b3d6c31-4267-45c6-bbee-d1ff757b688a)
