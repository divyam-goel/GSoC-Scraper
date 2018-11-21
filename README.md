# GSoC-Scraper
#### This program scrapes all the important information about organizations from the GSoC website.

### Information Retrieved:
1. Organization Name
2. Oraganization Tagline
3. Technologies/Topics
4. Total Projects in the Year
5. Link to Organization GSoC Page


### Usage:
Perform the following steps to successfully run the scraper: 
```
cd GSoc-Scraper
virtualenv gsoc_scraper
pip install -r requirements.txt
python scrape.py
```

### Note:
Currently this retrieves information for GSoC 2018. To change the year, change the url in the scrape.py file.
