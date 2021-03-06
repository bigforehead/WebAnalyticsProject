# Scrape Yelp

# Introduction
A delicious ice-cream scoop will be the best after a stressful day of work but where can I find the best place to go? I wrote a Python script to scrape Yelp to extract information about all the delicious ice-cream shop in town (Upper East Side where I used to live) and did some fun analysis with it to find what ice cream shop is the best to go.  

# Goals
This program is created to crawl basic information of Ice Cream shops from Yelp:
- Ranking
- Name
- Review
- Rating
- Phone
- Address
- District

# Methodology
- Crawl 100 Ice Cream shops on Yelp with BeautifulSoup
- Extract data from json file 
- Applied Pandas to output the information into one table
- Used matplotlib to visualize average rating and number of restaurant based on their location by district

