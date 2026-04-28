#  Web Scraping & API Data Collection

A Python project to collect real-world data for Machine Learning using web scraping and REST APIs.

---

##  Files

| File | Description |
|------|-------------|
| `Web_scraping.ipynb` | Scrapes 1000 books from books.toscrape.com |
| `API.ipynb` | Fetches crypto market data from CoinGecko |
| `Book_dataset.csv` | 1000 books — Name, Rating, Price, Stock |
| `Crypto.csv` | Crypto coins — Price, Market Cap, Volume |

---

##  Libraries Used

```bash
pip install requests beautifulsoup4 pandas lxml
```

---

##  How to Run

1. Clone the repo
2. Install libraries above
3. Open any `.ipynb` file in Jupyter and run all cells

---

##  What I Learned

- Web scraping with `requests` + `BeautifulSoup`
- Fetching data from REST APIs
- Handling pagination and rate limits
- Saving clean datasets with `pandas` for ML use
