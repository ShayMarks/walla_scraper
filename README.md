# 📰 Web Scraper for Walla! News Articles

## 📌 Overview

This project is a Python script for scraping news articles from **Walla! News**. It extracts detailed information such as titles, summaries, publication dates, authors, and article contents, and stores them in both CSV and Excel formats. This script is intended for **educational purposes** to demonstrate web scraping techniques with Selenium and data handling with pandas.

## ⚠️ Disclaimer

This scraper is designed for **educational purposes only**. The data retrieved belongs to Walla! News and is subject to their copyright and terms of use. Users are advised to comply with Walla!'s legal requirements and copyright policies before deploying this script in any form that could potentially distribute or publicly display Walla! content.

## 🚀 Features

- Scrape news articles directly from Walla! News.
- Collect articles data: title, summary, publication date, author name, main image URL, and content snippet.
- Save the extracted data into CSV and Excel files with formatting and design considerations.
- Pagination handling to process multiple pages (not implemented in the current script but can be added).

## 🛠 Prerequisites

Ensure you have the following installed on your machine before running the script:

- Python 3.8 or above
- Selenium WebDriver
- pandas library
- openpyxl library for Excel manipulation

## 🔧 Installation

1. Clone this repository to your local machine.
2. Install the required Python packages:
   ```bash
   pip install selenium pandas openpyxl
   ```
   3.Make sure to have ChromeDriver installed that matches your Chrome browser version. Place the `chromedriver.exe` in a known path.

## ⚙️ Setup and Execution

To run the script, follow these steps:

1. Open your terminal or command prompt.
2. Navigate to the project directory where the script is located.
3. Run the script using Python:
   python `app.py`

## 📄 Data Handling

The script captures and saves the data into `walla_news.csv` and `walla_news.xlsx` files. The Excel file is formatted for better readability with styles applied to headers and cells.

## 📋 Code Description

The script uses Selenium to open Walla! News, navigate through the articles, and extract the necessary details which include navigating to individual article pages. The use of `time.sleep()` is for simplicity, and it's advisable to use more robust waiting methods in production code.

## 🤖 Technology Stack

- **Python**: Programming language.
- **Selenium**: Tool for automating web browsers.
- **pandas**: Library for data manipulation and analysis.
- **openpyxl**: Python library to read/write Excel 2010 xlsx/xlsm files.

## 📘 License

This project is open-sourced under the MIT license. However, the data scraped belongs to Walla! News and should be used according to their policy.

## 👤 Author

### 👨‍💻 Shay Marks

### 💬 Contributing

Contributions, issues, and feature requests are welcome.

### 🌟 Support

Give a ⭐️ if this project helped you!

### 📖 References

- Selenium Documentation: [https://selenium-python.readthedocs.io/](https://selenium-python.readthedocs.io/)
- pandas Documentation: [https://pandas.pydata.org/pandas-docs/stable/](https://pandas.pydata.org/pandas-docs/stable/)
- openpyxl Documentation: [https://openpyxl.readthedocs.io/en/stable/](https://openpyxl.readthedocs.io/en/stable/)

### 📞 Contact

For any inquiries or further information, you can contact me at nrexhd@gmail.com.
