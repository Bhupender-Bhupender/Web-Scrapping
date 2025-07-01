# 🕸️ GitHub Topics Scraper

This project demonstrates **dynamic web scraping** of the [GitHub Topics page](https://github.com/topics) using Python. The scraper collects data about trending repositories under each topic — including repository names, URLs, descriptions, and star counts — and organizes them into a structured format.

---

## 📌 Project Objectives

- Scrape all programming and tech-related **topics** listed on GitHub
- For each topic, extract:
  - Topic title
  - Top repository names
  - Repo descriptions
  - Repo URLs
  - Number of stars
- Save the results in CSV format or display them cleanly in tables

---

## 🛠️ Tools and Libraries Used

- `requests` — to make HTTP requests to GitHub
- `BeautifulSoup` — to parse and extract HTML content
- `pandas` — to clean, store, and display scraped data
- `os` & `scrapy` (used optionally)

