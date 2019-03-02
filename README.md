# GSoC-Scraper
#### This program scrapes all the important information about past years' organizations from the archive of GSoC website.

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
```
* For information of all the organizations:
```
python scrape.py
```

* For information of organizations of a particular organization:
```
python scrape.py <Required Category Here>
```
For example, for information about all organizations of the category 'Operating Systems', do:
```
python scrape.py Operating Systems
```



### Note:
Currently this retrieves information for GSoC 2018. To change the year, change the url in the scrape.py file.
