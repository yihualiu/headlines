# Political headlines

### Abstract

This project examines headlines from [Politico](http://www.politico.com), an American political journalism web site. We scrape the headlines from stories published in the 66-week period between August 3, 2015 (the week of the first presidential debate) and November 7, 2016 (the day before the election). Politico's search feature can be manipulated by inserting start and end dates into a URL. The HTML from each page of the search results is then parsed to extract the headline text.

### Data

Politico's search feature can be found [here](http://www.politico.com/search?q=). After clicking "Advanced Search," we selected "Story" as the content type and "Oldest" as the sort method. The start and end dates can be selected on the page itself, but we manipulate them through the URL. When a search is performed, 20 results are returned per page. Pages can be selected at the bottom.

### Files

Because the scraping process can take a long time, the scraped data have been included in this repository for convenience. This allows a user to load the text directly from the local environment, which is much faster. The text files can be found under [/data](/data). If a user wishes to generate the files, the steps in [the first notebook ](/1_Data_scraping_and_parsing.ipynb) will allow the user to do so. These files will be created under [/processed](/processed).

Three annotated Jupyter notebooks cover each part of the project in detail. They contain all the code and print-outs along with explanatory analysis.
