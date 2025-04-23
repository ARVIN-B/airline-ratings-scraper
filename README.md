# AirlineRatings Scraper

This is a Python-based web scraper designed to extract airline safety and product ratings from [AirlineRatings.com](https://www.airlineratings.com). The collected data can be used for research, visualization, or general analysis of airline performance and safety metrics.

## ✈️ Features

- Scrapes airline names, safety ratings, and product ratings
- Saves data into a structured CSV format
- Uses `requests` and `BeautifulSoup` for HTML parsing
- Automatically loops through all pages on the site

## 🧰 Technologies Used

- Python 3
- requests
- BeautifulSoup (bs4)
- pandas
- tqdm (optional progress bar)

## 📁 Output

The scraper outputs a file named `airline_ratings.csv` that includes:

- Airline name
- Safety rating (out of 7)
- Product rating (out of 7)

## 🚀 How to Run

1. Make sure you have Python installed.
2. Install required packages:

'''bash
pip install requests beautifulsoup4 pandas tqdm
'''

3. Run the notebook or script:

open the airlineratings.ipynb file in Jupyter Notebook and run all cells.

📌 Notes

- The scraper navigates through multiple pages using the pagination system.
- AirlineRatings.com may change its structure over time; scraping logic might need updates accordingly.

📝 License
This project is open-source and available under the MIT License.

📬 Contact
For questions or suggestions, feel free to open an issue or contact me through GitHub.
