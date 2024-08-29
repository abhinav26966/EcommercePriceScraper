# Ecommerce Price Scraper

![License](https://img.shields.io/github/license/abhinav26966/EcommercePriceScraper)
![Last Commit](https://img.shields.io/github/last-commit/abhinav26966/EcommercePriceScraper)
![Issues](https://img.shields.io/github/issues/abhinav26966/EcommercePriceScraper)

A web scraping tool designed to fetch the latest prices of products from various e-commerce websites.

## Features

- **Multi-Platform Support**: Scrapes prices from multiple e-commerce platforms.
- **Real-time Updates**: Fetches the most recent price data.
- **Customizable**: Allows users to add or remove e-commerce sites.
- **Export Data**: Supports exporting scraped data in multiple formats (CSV, JSON, etc.).

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- Pip
- Virtual Environment (Optional but recommended)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/abhinav26966/EcommercePriceScraper.git
   cd EcommercePriceScraper
   ```

2. Set up a virtual environment (optional but recommended):
  ```bash
  python3 -m venv venv
  source venv/bin/activate   # On Windows use `venv\Scripts\activate`
  ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Configure the scraper:

  - Edit the config.json file to specify the e-commerce websites, products, and other settings.

2. Run the scraper:

   ```bash
   python scraper.py
   ```

3. View results:

  - The scraped data will be available in the output/ directory by default.


### Example

Here's a basic example of how to run the scraper:

```bash
  python scraper.py --site amazon --product "Samsung Galaxy S21"
```

### Supported Sites

- Amazon
- eBay
- Walmart
- Flipkart

### Contributors

  - Abhinav Nagar
