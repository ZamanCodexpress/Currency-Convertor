# Currency Converter

A sleek **client-side Currency Converter** built using **HTML, CSS, and vanilla JavaScript**. The application allows users to instantly convert between world currencies using live exchange rates — no backend, no frameworks, no setup required.

---

## Overview

This is a **single-page frontend application** designed for fast and simple currency conversion. Users can select a source currency and a target currency, enter an amount, and instantly get the converted result.

The app fetches **real-time exchange rates** from an external currency API, ensuring accurate and up-to-date conversions.

---

## Features

###  Currency Conversion
* Enter any amount to convert
* Select **From** and **To** currencies from a full list of world currencies
* Click **Convert** to get the live result instantly

###  Live Exchange Rates
* Fetches real-time rates from an external exchange rate API
* Always up-to-date conversion results

###  Clean UI
* Minimal, intuitive interface
* Responsive layout for desktop and mobile use
* Smooth user experience with straightforward controls

---

## Technologies Used

* HTML5
* CSS3 (Responsive Design)
* JavaScript (ES6+)
* Exchange Rate API (external, fetched at runtime)

---

## Project Structure

```text
├── index.html    # Application layout and structure
├── style.css     # Styling and responsive design
├── script.js     # Conversion logic and API integration
```

---

## Setup & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/ZamanCodexpress/Currency-Convertor.git
   ```
   **OR** download the project as a `.zip` file and extract it.

2. Open `index.html` in any modern web browser.

> No build tools, dependencies, or server setup required.

---

## Implementation Details

* Currency dropdown options populated dynamically via JavaScript
* API call triggered on **Convert** button click
* Exchange rate response parsed and displayed in the UI
* Error handling for invalid inputs or failed API requests

---

## Limitations

* Requires an active internet connection to fetch live exchange rates
* No offline/cached rate fallback
* No conversion history or tracking
* No backend or user authentication

---

## License

This project is **open-source** and intended for **educational and portfolio use**.

---

## Author

Designed and developed by **Zaman Siraj**
