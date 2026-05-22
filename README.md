# PakWheels Car Scraper 🚗

A Python-based web scraper for extracting used car listings from PakWheels using Selenium and BeautifulSoup.

This scraper allows you to:

- Open PakWheels listings
- Manually scroll the page
- Scrape all loaded car listings
- Save data into a CSV file

---

# Features ✨

- Scrapes:
  - Car Title
  - Price
  - Location
  - Year
  - Mileage
  - Fuel Type
  - Engine Capacity
  - Transmission

- Manual scrolling support
- CSV export
- Simple and beginner-friendly code

---

# Technologies Used 🛠️

- Python
- Selenium
- BeautifulSoup4
- Pandas

---

# Installation 📦

## 1. Clone Repository

```bash
git clone https://github.com/your-username/pakwheels-car-scraper.git
cd pakwheels-car-scraper
```

---

## 2. Install Dependencies

```bash
pip install selenium beautifulsoup4 pandas
```

---

## 3. Install ChromeDriver

Download ChromeDriver matching your Chrome version:

https://chromedriver.chromium.org/downloads

Add ChromeDriver to your system PATH.

---

# Usage 🚀

Run the script:

```bash
python scraper.py
```

---

# How It Works ⚙️

1. Opens PakWheels used car page
2. Waits for manual scrolling
3. User scrolls the page to load more listings
4. Press ENTER in terminal
5. Scraper extracts all loaded cars
6. Saves results into CSV file

---

# Output 📄

The scraper generates:

```text
pakwheels_karachi_cars.csv
```

Example CSV columns:

| Title | Price | Location | Year | Mileage | Fuel | Engine | Transmission |
|------|------|------|------|------|------|------|------|

---

# Example Output ✅

```text
Car #1
Title: Honda Civic 2005
Price: PKR 23.5 lacs
Location: Karachi
Year: 2005
Mileage: 96,686 km
Fuel: Petrol
Engine: 1600 cc
Transmission: Automatic
```

---

# Project Structure 📁

```text
pakwheels-car-scraper/
│
├── scraper.py
├── pakwheels_karachi_cars.csv
├── README.md
```

---

# Notes ⚠️

- PakWheels may block aggressive scraping.
- Manual scrolling is used to ensure listings load properly.
- Use responsibly and respect website policies.

---

# Future Improvements 🚀

- Automatic scrolling
- Multi-page scraping
- Proxy support
- Database integration
- Playwright support
- Image downloading

---

---

# License 📜

This project is licensed under the MIT License.