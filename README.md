# LinkedIN-WebScraper
Custom automated tool to pull professional user profiles using PlayWright, Python, and Pandas
# 🕵️‍♂️ LinkedIn Financial Advisors Scraper (Playwright + Bing Dorks)

This Python script automates the collection of **LinkedIn profile URLs** for freelance financial advisors using **Playwright** and **Bing search dorking**.

It performs a headless (or optionally visible) search of Bing results, scrapes valid `linkedin.com/in/` profile links, parses the first name from each profile, and exports everything into a structured `.csv` file.

---

## 📌 Features

- 🔍 Automates Bing queries to collect LinkedIn profile links
- 🎯 Targets "Freelance Financial Advisors" with a customizable query
- 🧠 Extracts first names from LinkedIn URLs
- 📝 Outputs results to a timestamped CSV file
- 🔁 Loops through up to 100 search pages (configurable)

---

## ⚙️ Requirements

- Python 3.7+
- [Playwright (async)](https://playwright.dev/python/docs/intro)
- Bing access (public, no API key needed)

Install dependencies:

```bash
pip install playwright
playwright install
