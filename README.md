This project contains a Jupyter Notebook with Python code designed to extract data from websites through web scraping. To handle fetching issues efficiently, the implementation utilizes the Scrape API Nina rotation method. The extracted data follows a structured approach by first capturing categories and then extracting products through pagination. The data is initially stored in JSON format and later converted into a CSV file for easier analysis and automation.

Features

Web Scraping Automation: Extracts data efficiently from websites.

Scrape API Nina Rotation: Helps to avoid fetching issues and ensures smooth data extraction.

Category & Product Extraction: First extracts categories, then drills down to individual products.

Pagination Handling: Navigates through multiple pages to extract complete data.

JSON to CSV Conversion: Stores data in JSON format and later converts it into CSV.

Automation with Selenium: Uses Selenium and WebDriver Manager for browser automation.

Technologies Used

Python: Primary programming language.

Selenium: Used for browser automation.

WebDriver Manager: Manages browser drivers automatically.

Scrape API Nina Rotation: Handles request rotation to prevent blocking.

JSON & CSV Handling: Converts extracted data from JSON to CSV.

Installation Guide

Clone the Repository

git clone https://github.com/MHemanth21/Web_Scraping.git
cd yourrepository

Create a Virtual Environment (Optional but Recommended)

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

Install Required Dependencies

pip install -r requirements.txt

Step-by-Step Execution

Import Required Libraries

Load necessary libraries such as selenium, webdriver_manager, json, csv, and requests.

Initialize Web Driver

Use WebDriver Manager to install and initialize the appropriate browser driver.

Handle Fetching Issues Using Scrape API Nina Rotation

Set up Scrape API Nina to rotate requests and bypass rate limits or blocks.

Extract Categories

Scrape category data first to structure the extraction process.

Extract Products Through Pagination

Iterate through multiple pages to gather all products within each category.

Store Data in JSON Format

Save the extracted data into a structured JSON file.

Convert JSON to CSV

Parse the JSON file and convert it into CSV format for easier processing and analysis.

Usage

Run the Jupyter Notebook step by step to extract data.

Modify the scraping URLs or parameters based on the target website.

Adjust the Scrape API rotation settings if required.

Use the CSV output for further analysis or automation tasks.

Notes

Ensure that Selenium and WebDriver Manager are properly installed before execution.

Modify the scraping logic if the website structure changes.

Respect the website's robots.txt policy and terms of service while scraping.

License

This project is licensed under the MIT License - see the LICENSE file for details.
