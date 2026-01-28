# SDET SAT – Hotel Price Scraper (Playwright + JavaScript)

This project is created as part of the SDET Skill Assessment Test.

It uses **Playwright with JavaScript** to automate Booking.com and find the lowest listing price for a 5-night stay for:

- 2 Adults
- 1 Infant (age < 2 years)

At the highest-rated 5-star hotel in a given city.

---

## What the script does

1. Opens Booking.com for a given city
2. Applies 5-star hotel filter
3. Sorts hotels by highest rating
4. Opens the top-rated hotel
5. Tries multiple future 5-night date ranges
6. Extracts the price for each date range
7. Prints the lowest price found

---

## Tech Used

- Node.js
- Playwright
- JavaScript

---

## Project Structure

hotel-scraper
 ├─ src
 │   ├─ scraper.js
 │   └─ dateHelper.js
 ├─ package.json
 ├─ README.md

---

## How to Run

npm install  
npx playwright install  
node src/scraper.js

---

## Notes

- Target website: Booking.com
- No hardcoded hotel names or prices
- Dates are future dates within the calendar year