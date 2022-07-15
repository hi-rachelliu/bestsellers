# Bestsellers

## Overview

Analysis and visualizations of data from the New York Times on NYT bestsellers from January 3, 2010 to December 29, 2019.

## Data Dictionary

| Field              | Description                                       |
|--------------------|---------------------------------------------------|
| published_date     | Date the list was published                       |
| list_name          | Book category                                     |
| list_name_encoded  | Encoded category                                  |
| rank               | Rank on the list for that week                    |
| isbn13             | ISBN 13 of the book                               |
| isbn10             | ISBN 10 of the book                               |
| title              | Title of the book                                 |
| author             | Author of the book                                |
| description        | Description of the book                           |
| amazon_product_url | Amazon URL                                        |
| price              | Price of the book                                 |
| weeks_on_list      | Number of weeks the book was on Best Sellers list |

## Relevant Files

-   bestsellers.Rmd: An Rmd file which contains exploration and visualizations for NYT bestseller data, dating from 03-Jan-2010 to 29-Dec-2019
-   bestsellers.Rmd: An md file which contains all code and resulting output
-   bestsellers.csv: a csv file which contains NYT bestseller data, originally downloaded from [Kaggle](https://www.kaggle.com/datasets/dhruvildave/new-york-times-best-sellers)

## Execution

Run bestsellers.Rmd from top to bottom to successfully knit a finished report with figures included!
