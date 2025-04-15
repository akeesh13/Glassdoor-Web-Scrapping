# 💼 Glassdoor Job Listings Web Scraper

This Python-based project scrapes job listings from **Glassdoor** for various roles such as **Data Analyst**, **Software Developer**, and more. It extracts key details like **job title**, **company name**, **location**, **salary estimates**, **company ratings**, and **job summaries**. The scraped data is saved in a **CSV** file for further analysis.

---

## 📌 Project Features

- Scrapes job listings for any given role (e.g., "Data Analyst", "Software Developer") from **Glassdoor**.
- Extracts the following information:
  - **Job Title**
  - **Company Name**
  - **Location**
  - **Salary Estimates**
  - **Company Rating**
  - **Job Summary/Description**
- Automatically handles pagination (i.e., moves to the next page to scrape more job listings).
- Exports the scraped data to **CSV** for easy analysis.

---

## 🛠️ Tech Stack

- **Python**
- **Selenium** – For web automation and scraping dynamic content
- **BeautifulSoup** – For parsing HTML and extracting structured data (if needed)
- **Pandas** – For handling and exporting data (if you plan to do additional processing)
- **CSV** – For saving the scraped data
- **Time** – For implementing delays between requests to prevent overloading the server

---

## 🚀 How to Run

1. **Clone the repo:**
   ```bash
   git clone https://github.com/akeesh13/glassdoor-job-scraper.git
   cd glassdoor-job-scraper
