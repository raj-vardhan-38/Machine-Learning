# Web Scraping

This project is a Python notebook for scraping company listing data from AmbitionBox using `requests` and `BeautifulSoup`.

## Project Files

- `webScraping.ipynb` - main notebook for scraping and extracting the data

## What It Does

- Sends HTTP requests to the target page.
- Parses the HTML with BeautifulSoup.
- Extracts company listing details from the page content.

## Requirements

The notebook uses the following Python packages:

- `requests`
- `beautifulsoup4`
- `lxml`

You can install them with:

```bash
pip install requests beautifulsoup4 lxml
```

## How to Run

1. Open `webScraping.ipynb` in Jupyter or VS Code.
2. Run the cells from top to bottom.
3. Make sure the notebook has internet access when it makes the request.

## Notes

- Web pages can change over time, so scraping selectors may need updates later.
- Check the target website's terms of use and robots policy before reusing the scraper.