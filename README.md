
# Apollo Data Scrape

Apollo Data Scrape is a Python project designed to scrape data from a saved search list in the Apollo app using a paid account. This tool targets decision-making personnel within various companies, collecting essential data such as company names, personal names, designations, phone numbers, and emails. The scraped data is then saved into a CSV file for easy analysis and usage.

## Prerequisites

To run this project, ensure you have the following requirements set up on your PC:

- **Python**: Ensure you have the latest version of Python installed. [Download Python](https://www.python.org/downloads/)
- **Selenium**: This project uses Selenium for web scraping. You can install it via pip:
  ```bash
  pip install selenium
  ```
- **Firefox Browser**: Apollo Data Scrape uses Firefox for browsing web pages. Make sure Firefox is installed on your system. [Download Firefox](https://www.mozilla.org/en-US/firefox/new/)
- **Geckodriver**: This must be installed and placed in the same directory as the main `run.py` file or added to your system's PATH. [Download Geckodriver](https://github.com/mozilla/geckodriver/releases)

## Setup and Execution

1. **Clone the Repository**: First, clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/apollo_data_scrape.git
   cd apollo_data_scrape
   ```

2. **Configuration**: Make sure to configure your Apollo account settings and desired search parameters within the script or via a configuration file.

3. **Run the Script**: Execute the `run.py` file to start the data scraping process:
   ```bash
   python run.py
   ```

## Data Collection

The script will navigate through the Apollo app's saved searches, extracting the following information:
- Company Name
- Person's Name
- Designation
- Phone Number
- Email

The data will be collected and saved in a CSV file named `output.csv`, located in the project directory.

## Disclaimer

This tool is intended to be used with a legitimate Apollo app paid account and in compliance with Apollo's terms of service. Users are responsible for ensuring that their use of this script complies with legal and ethical standards.
