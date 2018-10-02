# Python WebScraper
A simple python webscraper that uses BeautifulSoup 4 and other libraries.
Will be updating with cool new functions as I go along.

# Ensure you have the latest version of Python
Install Python 3.6.5 available on Windows/Linux here https://www.python.org/downloads/

# Upgrade pip and install BeautifulSoup3
pip install --upgrade pip #if not already up to date
pip install requests BeautifulSoup4

# Download scraper.py and cd to location of script
cd /locationOfScraper
python
from scraper import simple_get
raw_html = simple_get('www.whatever_url_in_here.com')

# The raw_html variable will now hold the raw text of the url you entered, unless error is occured,
# if this is the case then error log will print

