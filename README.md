
# E-commerce Data Extraction and Analysis: Nykaa Product Insights 

Exploring product trends in the beauty market using data analysis.

## Project Overview

This project involves web scraping, data preprocessing, and exploratory data analysis (EDA) of lipstick product listings from Nykaa, a popular beauty e-commerce platform.

Data was scraped using the Requests library, BeautifulSoup, and Regular Expressions (re). The extracted information includes:

* Product Name
* Brand
* Price
* Offer Price
* Discount / Offer Percentage
* Ratings
* Number of Reviews
* Coupon Availability

After extraction, the dataset was cleaned and preprocessed to remove inconsistencies. EDA was then performed to analyze trends in pricing, discounts, ratings, and brand popularity.

## Objectives

* Scrape lipstick product details from Nykaa
* Clean and preprocess the extracted dataset
* Perform EDA to identify trends and patterns
* Visualize findings clearly and effectively
* Understand consumer preferences in the beauty segment

## Technologies Used

| Category           | Libraries                           |
| ------------------ | ----------------------------------- |
| Web Scraping       | requests, BeautifulSoup, re         |
| Data Manipulation  | pandas, numpy                       |
| Data Visualization | matplotlib, seaborn                 |
| Analysis Type      | EDA, trend and correlation analysis |

## EDA Highlights

The analysis includes:

* Identification of the most popular brands based on reviews
* Study of the relationship between price and ratings
* Impact of discounts on final price
* Distribution of product prices
* Top discounted lipsticks
* Correlation insights using heatmaps

Visualizations include:

* Countplot
* Boxplot
* Scatterplot
* Barplot
* Lineplot
* KDE Plot
* Heatmap
* Pairplot
* Pie Chart

## Project Structure

```
Nykaa-Lipstick-EDA
│
├── README.md
├── nykaa_lipstick_scraping.ipynb
├── eda_analysis.ipynb
├── nykaa_lipsticks.csv
└── requirements.txt (optional)
```

## Key Learnings

* Improved understanding of HTML structure during web scraping
* Enhanced skills in data cleaning and preprocessing
* Better understanding of real-world product insights through EDA
* Gained experience in visual storytelling using Python visualization libraries

## Future Improvements

* Perform sentiment analysis on product reviews (NLP integration)
* Build a machine learning model for price prediction
* Create an interactive dashboard using Streamlit or Power BI
* Expand the dataset by scraping multiple product categories
