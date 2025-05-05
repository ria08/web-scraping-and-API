# 🕷️ Web Scraping Projects Portfolio

A collection of three data scraping projects showcasing different scraping methods—HTML scraping with `requests` and `BeautifulSoup`, and API scraping using `RapidAPI`. Each project involves data extraction, preprocessing, and storing the results in a structured format for analysis.

---

## 📑 Table of Contents

- [📦 Project 1: Flipkart UHD TVs Scraper](#-project-1-flipkart-uhd-tvs-scraper)
- [📚 Project 2: Goodreads Dystopian Books Scraper](#-project-2-goodreads-dystopian-books-scraper)
- [🐦 Project 3: Twitter API Scraper](#-project-3-twitter-api-scraper)


- ## 📦 Project 1: Flipkart UHD TVs Scraper

**Objective**: Scrape UHD TV product listings from Flipkart for basic price and feature comparison.

- **Source**: [flipkart.com](h[ttps://www.flipkart.com](https://www.flipkart.com/search?count=40&otracker=CLP_filters&p%5B%5D=facets.smart_tv%255B%255D%3DYes&p%5B%5D=facets.resolution%255B%255D%3DUltra%2BHD%2B%25284K%2529&sid=ckf%2Fczl&otracker=nmenu_sub_TVs+and+Appliances_0_Smart+and+Ultra+HD&otracker=nmenu_sub_TVs+%26+Appliances_0_Smart+%26+Ultra+HD&page=1))
- **Method**: HTML scraping using `requests` and `BeautifulSoup`
- **Pages Scraped**: 10
- **Total Rows**: 240 products
- **Columns**: 7 (`Name`, `Price`, `Rating`, `Discount`, `Launch Year`, `Operating System`, `Delivery Type`)
- **Output**: CSV file

### Key Learnings:
- Pagination handling
- Dealing with inconsistent HTML tags and missing data
- Headers and user-agent spoofing

---

## 📚 Project 2: Goodreads Dystopian Books Scraper

**Objective**: Extract book details for dystopian genre to analyze popularity and patterns.

- **Source**: [goodreads.com]([https://www.goodreads.com](https://www.goodreads.com/list/show/47.Best_Dystopian_and_Post_Apocalyptic_Fiction?page=1))
- **Method**: HTML scraping using `requests` and `BeautifulSoup`
- **Pages Scraped**: 40
- **Total Rows**: 3,636 books
- **Columns**: 6 (`Book Title`, `Author`, `Ratings`, `Avg Rating`, `Score`, `Total Votes`)
- **Output**: CSV file

### Key Learnings:
- Extracting nested data in HTML
- Managing large pagination without server blocking
- Parsing numeric and textual data from strings

---

## 🐦 Project 3: Twitter API Scraper

**Objective**: Collect tweet and user metadata using RapidAPI to experiment with API data extraction.

- **Source**: [RapidAPI - twitter154.p.rapidapi.com](https://rapidapi.com)
- **Method**: API scraping using `requests` and API key authentication
- **Total Rows**: 83 tweets
- **Columns**: 27 (tweet_id, creation_date, text, media_url, video_url, user, language, favorite_count, retweet_count, reply_count, quote_count, retweet, views, timestamp, video_view_count, in_reply_to_status_id, quoted_status_id, binding_values, expanded_url, retweet_tweet_id, extended_entities, conversation_id, retweet_status, quoted_status, bookmark_count, source, community_note)
- **Output**: CSV or JSON
