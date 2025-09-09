OLX Car Cover Scraper

This project is a simple Python script that scrapes Car Cover listings from OLX India
 using Selenium and saves the results into a CSV file.

📌 Features

Extracts Title, Price, and Location of each listing

Handles dynamic content loading by scrolling down the page

Saves the results in olx_car_cover_results.csv

Optionally, filter results to only include rows containing "car cover"

🛠️ Tech Stack

Python 3

Selenium

Pandas

Webdriver Manager (to auto-manage ChromeDriver)

📂 Project Structure
olx-assignment/
│── olx_scraper.py         # Main scraper script
│── requirements.txt       # Required Python packages
│── README.md              # Project documentation

🚀 How to Run

Clone this repository

git clone https://github.com/Upasana29/olx-assignment.git
cd olx-assignment


Install dependencies

pip install -r requirements.txt


Run the scraper

python olx_scraper.py


After execution, check the generated CSV file:

olx_car_cover_results.csv
