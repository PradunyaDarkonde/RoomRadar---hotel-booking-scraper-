# 🛰️ RoomRadar — Hotel Booking Scraper

> ⚙️ **Technical & Direct**  
> Automates the extraction of hotel listings from Booking.com using BeautifulSoup and Requests. Provides customizable URL input and stores results in CSV format.

---

## 📌 Project Overview  
RoomRadar is a Python-based web scraper built to extract hotel details from [Booking.com](https://www.booking.com). It fetches information like hotel name, price, location, ratings, review count, and booking link for a given city and date range, then stores it neatly in a CSV file.

---

## 🎯 Objectives
- **Automate Hotel Data Collection** – Extract key hotel details quickly and efficiently.
- **Customizable Searches** – Users can input any Booking.com search URL and output file name.
- **Structured Storage** – Save data in a clean, readable CSV format.
- **Anti-Blocking Features** – Uses headers and random sleep to simulate human browsing.
- **Command-Line Friendly** – Lightweight, easy-to-use script from your terminal.

---

## 🔧 Technologies & Libraries Used
- **Python 3.x**
- `BeautifulSoup4` – For parsing HTML and extracting hotel details  
- `Requests` – To send HTTP requests to Booking.com  
- `LXML` – Fast, efficient HTML parser  
- `CSV` – For saving structured data

---

## 📂 Features & Workflow

1. Run the script and enter a **Booking.com search URL** and **desired output filename**.
2. The script scrapes and extracts:
   - 🏨 **Hotel Name**
   - 💰 **Price**
   - 📍 **Location**
   - ⭐ **Rating**
   - 📝 **Review Count**
   - 🔗 **Booking Link**
3. All the extracted data is saved into a **CSV file** in your local directory.
4. Implements:
   - ⏱️ **Randomized sleep intervals** between requests  
   - 🛡️ **Request headers** to avoid scraping blocks

---

## 🚀 How to Run

### 1. Install Required Packages
```bash
pip install beautifulsoup4 requests lxml

---

## Run the Script
python script.py

###  Provide Inputs When Prompted
Paste the Booking.com search URL (with city and dates)

Enter your desired CSV file name (e.g., hotels.csv)

The data will be scraped and saved to your specified file.


