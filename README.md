# BuyMe Catalog Sorter

A small static web tool for searching, filtering, sorting, and exporting Israeli businesses that accept BuyMe gift cards.

The project started from a ChatGPT conversation about turning a BuyMe listing page into a sortable catalog. It is designed to run as a simple `index.html` file, which also makes it easy to publish with GitHub Pages.

## Features

- Search across business names, categories, regions, contact details, terms, and descriptions
- Filter by category, subcategory, region, online redemption, and multiple-voucher support
- Sort by any visible table column
- Export filtered results to CSV
- Export a full Excel workbook with Businesses, Products, Categories, and Regions sheets
- Runs without a backend

## Data Source

The app loads catalog data from:

```text
https://raw.githubusercontent.com/eladkishon/buyme-mcp/main/data/buyme.json
```

That dataset is maintained by the community project [`eladkishon/buyme-mcp`](https://github.com/eladkishon/buyme-mcp). Its README says the catalog is refreshed automatically every Monday at 04:00 UTC.

This project is not affiliated with BuyMe. Prices, terms, and participating businesses may be stale, so verify important details on the official BuyMe site before relying on them.

## Usage

Open `index.html` in a browser, or publish it with GitHub Pages.

Internet access is required because the app loads the current catalog JSON and the Excel export library from public CDNs.

## Suggested GitHub Repo Details

- Repository name: `buyme-catalog-sorter`
- Description: `Static web tool for searching, sorting, filtering, and exporting BuyMe catalog data.`
- Topics: `buyme`, `catalog`, `gift-cards`, `israel`, `static-site`, `csv-export`, `excel-export`

## GitHub Pages

After uploading this project to GitHub:

1. Go to repository settings.
2. Open **Pages**.
3. Choose deployment from the `main` branch.
4. Select the repository root as the source.
5. Save.

GitHub will publish the app at a URL like:

```text
https://TomerSY.github.io/buyme-catalog-sorter/
```

## License

MIT
