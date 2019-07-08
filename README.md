# Predicting Tabletop Game Success

## Overview
Despite the growing trend towards digital singularity, tabletop games have seen unprecedented success. In 2017 alone, more than 5,000 board games were introduced into the U.S. market.1 Given the growing success of tabletop games within recent years, this project seeks to construct a linear regression model that predicts the success of tabletop games. The application of this project lies with tabletop game designers and publishers alike, who can use this model to produce games that are optimized towards consumer desires.
## Project Organization
    ├── README.md             <- The top-level README for developers using this project
    │
    ├── LICENSE               <- Copyright and permissive license
    │
    ├── Notebooks             <- Project source code in Jupyter notebook
    │   └── project4.py       <- Script with helper functions
    │
    ├── Reports               <- Various reports
    │   ├── proposal.pdf      <- Project proposal
    │   ├── summary.pdf       <- Project summary
    │   └── presentation.pptx <- Project presentation slide deck
 

## Data
The data was obtained via scraping information for 8,712 tabletop games from boardgamegeek.com (BGG), a massive online games database with information and metrics on over 81,000 tabletop games. After cleaning the data to account for missing data and outliers, I was left with 5,537 observations.

Because tabletop game sales were not readily available to the public, I utilized average community rating as my target variable. Though the BGG community is not a perfect representation of the general public nor is average rating a perfect indicator of game success, it is the closest available proxy in the absence of sales data.

## Tools
* ***Web Scraping:*** BeautifulSoup, Selenium
* ***Data Processing:*** Pandas, NumPy
* ***Modeling:*** Scikit-learn, Statsmodels
* ***Data Visualization:*** Matplotlib, Seaborn
* ***Presentation:*** Powerpoint 

## LICENSE
MIT © Brooke Ann Coco

