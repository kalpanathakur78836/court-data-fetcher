# Court Data Fetcher

A simple Flask web app that lets you enter Indian court case details (Case Type, Case Number, Year) and shows the case information.

For this internship task, I chose to keep it in **sample data mode** (due to CAPTCHA restrictions on many court portals).  
The structure is ready for real scraping — you only need to implement the `fetch_case_real()` function in `scraper.py` for your chosen court.

---

## Features
- Simple web form for input
- Shows parties' names, filing date, next hearing date, and latest order link
- Logs each search to an SQLite database
- Bootstrap UI for a clean look

---

## How to Run
1. Install Python (version 3.8 or higher)
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
