# Google Maps Scraper
The Google Maps Scraper is a Python-based tool designed to automate the extraction of business information from Google Maps. Utilizing the Playwright library for web automation, this scraper performs targeted searches, collects business data, and compiles them into Excel and CSV files.

## Features
Automated Searches: Input search terms to find businesses on Google Maps.
Comprehensive Data Extraction: Gather essential business details such as names, addresses, websites, phone numbers, review counts, and average ratings.
Geolocation Information: Extract and store precise latitude and longitude coordinates for each business.
Output to Excel and CSV: Save the collected data into easily accessible Excel and CSV files.

## Requirements
Python 3.6 or higher
Playwright
Pandas
OpenPyxl

## Installation
Clone the repository:
```python
git clone https://github.com/yassazx/Google-Maps-Scraper.git
cd Google-Maps-Scraper
```

Install the required packages:
```python
pip install -r requirements.txt
```
## Usage
Prepare your search terms:

You can either pass search terms as an argument or list them in input.txt.
Run the scraper:
```python
python main.py -s "coffee shops in Paris"
```
Or without arguments, to use the terms in input.txt:
```python
python main.py
```

The results will be saved in the output directory in both .xlsx and .csv formats.
