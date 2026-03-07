# Currency Converter

A modern **client-side Currency Converter App** built using **HTML, CSS, and vanilla JavaScript**. The application allows users to instantly convert between world currencies using live exchange rates fetched from a public API — all without any backend or frameworks.

---

## Overview

This is a **single-page frontend application** designed to make currency conversion simple and accurate. Users select a source currency, a target currency, and enter an amount to receive a real-time converted result powered by live exchange rate data.

The app fetches live rates on load and on every conversion, ensuring the results are always up to date.

---

## Features

### Currency Conversion
- Convert between a wide range of world currencies
- Real-time exchange rates fetched from the **ExchangeRate API**
- Accurate results rounded to 2 decimal places
- Input validation to prevent negative or invalid amounts

---

### Dynamic Currency Options
- Currency dropdowns are populated dynamically from the API on page load
- No hardcoded currency list — always reflects available currencies from the live data

---

### User Interface
- Clean, dark-themed card layout
- Labeled form fields for amount, source currency, and target currency
- Conversion result displayed clearly below the form
- Smooth hover and focus transitions on inputs and buttons

---

### Responsive Design
- Optimized for desktop, tablet, and mobile devices
- Centered card layout adapts to all screen sizes
- Works on all modern browsers

---

## Technologies Used

- HTML5
- CSS3 (Responsive Layout + Dark Theme UI + CSS Custom Properties)
- JavaScript (ES6+, Async/Await, Fetch API)
- [ExchangeRate API](https://api.exchangerate-api.com) — live currency exchange rate data
- Google Fonts — Poppins typeface

---

## Project Structure

```text
├── index.html    # Application layout and form structure
├── style.css     # Dark theme styling, CSS variables, responsive design
├── script.js     # API calls, currency population, conversion logic
```

---

## Setup & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/ZamanCodexpress/Currency-Converter.git
   ```
   **OR** download the project as a `.zip` file and extract it.

2. Open `index.html` in any modern web browser.

> **Note:** An active internet connection is required to fetch live exchange rates from the ExchangeRate API.

No build tools, dependencies, or server setup required.

---

## Implementation Details

- Currency options are fetched on `window load` from `api.exchangerate-api.com/v4/latest/USD`
- Both `From` and `To` dropdowns are populated dynamically by iterating over the API's `rates` object
- On form submission, a second API call is made using the selected `From` currency as the base
- Converted amount is calculated as `amount × rate` and displayed in the result div
- CSS custom properties (variables) used throughout for consistent theming

---

## Limitations

- Exchange rates depend on the free tier of ExchangeRate API — update frequency may be limited
- No offline support or cached rates
- No swap button to quickly reverse the conversion direction
- No conversion history or persistent storage
- Currency names displayed as codes only (e.g., USD, EUR) — no full country names or flags

---

## License

This project is **open-source** and intended for educational and portfolio use.

---

## Author

Designed and developed by **Zaman Siraj**
