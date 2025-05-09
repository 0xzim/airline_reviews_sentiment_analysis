## ✈️ Airline Review (British Airways) Sentiment Analysis

### Overview
This project involves collecting and analyzing british airline review data from [Skytrax](https://www.airlinequality.com/airline-reviews/british-airways/page/1/), a leading airline and airport review website. The main goal was to perform sentiment analysis on customer reviews to understand how the travelers feel about their experiences using the airline.

### Objectives
* Scrape airline review data from the Skytrax website.
* Clean and transform the raw HTML data into structured analyzable format.
* Apply natural language processing (NLP) techniques to analyze sentiment using the VADER sentiment analyzer.


### Tools and Libraries
* Python
* BeautifulSoup – for web scraping
* Pandas – for data manipulation
* NLTK (VADER) – for sentiment analysis
* Matplotlib – for visualizations

### Sentiment Analysis
Before performing sentiment analysis, I removed empty reviews, reducing the dataset to 2,413 entries.
VADER is a lexicon and rule-based sentiment analysis tool tuned for social media and customer reviews.

Sentiment Classification Rules:

* Positive: compound ≥ 0.05
* Negative: compound ≤ -0.05
* Neutral: -0.05 < compound < 0.05

### Sentiment Results
Out of 2,413 reviews:

* 🟢 Positive: 1,230 reviews (50.97%)

* 🔴 Negative: 1,147 reviews (47.53%)

* ⚪ Neutral: 36 reviews (1.49%)

**Insight**: The majority of airline reviews were polarized either strongly positive or negative with very few neutral responses.