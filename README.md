# Scraping code by using Scrapy

## Scraping data from [this site](https://mega-hatsu.com/article-for-sale/)

## Installation
1. Install Python 3.x
2. Install required packages
```
    pip install - r requireemnts.txt
```
    
    
3. Install PostgreSQL and set username and password

    username: posgres 
    
    password: root
## Run scrapy
In the root directory that scrapy.cfg is located, run the following command.

```
    scrapy crawl infos -O info.xlsx    
```
To save excel file with timeline, run the following command.
```
    scrapy crawl infos -O '%(time)s.xlsx'
```