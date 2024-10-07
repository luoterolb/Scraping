# 📚 Fiction Book Price Scraper

## 🚀 Project Overview

This project is a comprehensive **web scraping solution** that extracts book information and prices from the fiction section of the bookstore website **bookshop.com.uy**. By automating data collection, the goal is to build a monthly database to analyze price trends and evolution over time.

## 🔍 Key Features

- **Web Scraping with BeautifulSoup**: Efficiently scrapes multiple pages from the fiction section, gathering essential information for each book.
- **Detailed Book Information**: Collects and organizes data including:
  - Title, Price, Availability
  - ISBN, Author, Publisher
  - Edition, Language, Pages, Cover Type
  - Description
- **Data Transformation**: Cleans and processes the scraped data, transforming text to lowercase for consistency and adding a scraping timestamp to ensure traceability.
- **Export to CSV**: All the gathered book data is neatly compiled into a **CSV file** for further analysis.

## 📈 Main Purpose

By building this automated tool, we aim to create a **monthly dataset** that tracks price evolution in the fiction book market. This will enable:
- Trend analysis of book prices.
- Insights into how factors like availability, edition, or author impact pricing.
- A powerful dataset for predictive modeling and further exploration in the future.

## 🛠️ Technology Stack

- **Python Libraries**: 
  - `pandas` for data manipulation and export.
  - `BeautifulSoup` for web scraping.
  - `numpy` for data handling.
- **Web Scraping**: The script efficiently navigates and scrapes multiple pages of the bookstore’s fiction section.
  
## 📊 Conclusion

This project delivers a robust pipeline for collecting and organizing book price data. The ability to consistently track prices and book details over time will provide valuable insights into market trends and pricing strategies in the bookstore industry.
