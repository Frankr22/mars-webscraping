# Mars Web Scraping

This project is a web scraping project that scrapes data from the Mars Temperature Data Site (https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html) using the Python libraries Splinter and BeautifulSoup. The scraped data is then analyzed and visualized using the Pandas and Matplotlib libraries.

The project is divided into several steps:

- Automated browsing to visit the Mars Temperature Data Site and extract all rows of data
- Assemble the scraped data into a Pandas DataFrame.
- Clean the data by removing missing values and converting data types
- Analysing this data

## Data Analysis
Pandas functions are used to answer several questions:
- How many months exist on Mars?
- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
- What are the coldest and the warmest months on Mars (at the location of Curiosity)?
- Which months have the lowest and the highest atmospheric pressure on Mars?
- About how many terrestrial (Earth) days exist in a Martian year?
Matplotlib is used to visualize the results.
Data is then saved in a CSV file

The project uses the following Python libraries:
- Splinter
- BeautifulSoup
- Pandas
- Matplotlib
- webdriver_manager
To run this project, you will need to have Python and these libraries installed on your machine.

After installing the dependencies, you can run the Jupyter Notebook files to scrape the data, analyze it, and save it to a CSV file.

The resulting CSV file and the code are available in this GitHub repository, so you can examine the results, or use the code as a starting point for your own project.
