# BPS Export Statistics Web Scraper

**Overview**

This project is an automated Web Scraper written in Python designed to extract export value statistics (FOB in Million USD) grouped by major destination countries and regions from the official **Badan Pusat Statistik (BPS) Indonesia** portal.

It uses "undetected-chromedriver" to navigate dynamic web pages safely, "BeautifulSoup" to parse HTML structures, and "pandas" to clean and format tabular data.

**Project Structure**

```text
bps-export-scraper/
│
├── data/                  # Output directory (data automatically saves here)
│   └── bps_export_statistics.csv
│
├── main.py                # Main web scraping script
├── requirements.txt       # Project dependencies
├── .gitignore             # Folder for Ignored file
├── LICENSE                # Project License 
└── README.md              # Project documentation
