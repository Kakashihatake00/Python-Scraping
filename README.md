# Python Scraping – Recycling Facility Data

This repository contains my internship project, where the task was to:
> Build a traditional Python scraper (using Selenium or BeautifulSoup) to extract recycling facility data from search results and export it as a CSV file.

The data is scraped from [Earth911](https://search.earth911.com).

---

## 📚 Libraries Used
- `requests` – To send HTTP requests and access URLs
- `beautifulsoup4` – For parsing and extracting HTML data
- `csv` – For writing scraped data into a CSV file
- `pandas` – For reading and verifying the CSV output

---

## 🛠 Steps to Scrape Data
1. Send an HTTP request to the search results page.
2. Parse the HTML response using `BeautifulSoup`.
3. Extract company links from the search results.
4. Visit each company’s detail page to scrape:
   - Name
   - Last updated date
   - Location(s)
   - Accepted materials
5. Save the extracted data into a CSV file.
6. Use `pandas` to read and verify the data.

---

## ▶️ How to Run
```bash
git clone https://github.com/username/repository-name.git
cd repository-name
pip install -r requirements.txt
python scraper.py
```
---
## 📌 Notes
1. Make sure you have Python 3.8+ installed.

2. This project uses utf-8-sig encoding to avoid special-character issues in CSV output.



