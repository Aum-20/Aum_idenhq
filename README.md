# Aum_idenhq
# Product Data Scraper using Playwright

This project is an automated web scraping tool that logs into a website, navigates to a dashboard, and extracts product data using [Playwright](https://playwright.dev/python/). It supports session persistence, handles pagination, and exports the scraped data to a JSON file.

## Features

- Headless browser automation using Playwright.
- Automatic login with session reuse.
- Screenshots for debugging.
- Smart navigation through dynamic elements.
- Extracts detailed product information.
- Handles pagination gracefully.
- Saves product data in a structured JSON format.

## Requirements

- Python 3.7+
- [Playwright](https://playwright.dev/python/)
- `nest_asyncio` for running async functions in environments like Jupyter.

## Installation

1. Clone this repository or copy the script.

2. Install dependencies:
```bash
pip install playwright nest_asyncio
playwright install
