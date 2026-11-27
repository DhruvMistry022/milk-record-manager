# 🥛 Milk Record Manager

A simple, responsive household milk tracking website built with **HTML, CSS, and JavaScript**.

The complete application is contained in one file: `index.html`. No separate CSS or JavaScript files, server, PHP, or database are required.

## Features

- Dashboard with today's milk quantity, monthly litres, monthly cost, daily average, and recent records.
- Add, edit, search, filter, and delete daily milk records.
- Record separate morning and evening quantities.
- Automatically calculate daily quantity and cost.
- Monthly reports with date-wise breakdowns and totals.
- Mark each daily entry as Paid or Pending.
- Export records as a CSV spreadsheet file.
- Download and restore JSON backups.
- Light and dark mode.
- Responsive design for desktop and mobile screens.

## Run on a computer

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in Chrome, Edge, Firefox, or another modern browser.
4. Start adding your daily milk records.

No installation or build step is needed.

## Run on Android

1. Download the repository files or open the published GitHub Pages website.
2. To run locally, open `index.html` with Chrome from your file manager.
3. If your phone cannot open local HTML files, use the GitHub Pages website link instead.

## Publish with GitHub Pages

1. Create a public GitHub repository.
2. Upload `index.html` and `README.md` to the repository's root folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then save.
6. Wait for GitHub Pages to publish the site. The published URL will appear in the Pages section.

## How to add a milk record

1. Open the Dashboard and choose **Add record**.
2. Select the date.
3. Enter the morning and evening milk quantities in litres.
4. Enter the price per litre in Indian rupees (₹).
5. Select **Paid** or **Pending**.
6. Optionally add a note, then save the record.

The app calculates:
- **Total milk:** morning quantity + evening quantity
- **Daily amount:** total milk × price per litre
- **Monthly total:** sum of daily quantities and amounts for the selected month

Only one combined record per date is supported. If you save another record for an existing date, the app asks whether you want to replace the existing entry.

## Data storage and backup

- Records are stored in browser **LocalStorage** on the device where the website is used.
- Records do not automatically synchronize between different browsers or devices.
- Clearing browser storage may permanently remove records.
- Use **Backup & settings → Download backup** regularly.
- Use **Restore backup** to import a previously downloaded JSON backup. Entries with matching dates are replaced by imported entries.

## Project structure

```text
milk-record-manager/
├── index.html
└── README.md
```

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Browser LocalStorage

## Notes

This project is intended for personal household milk tracking. It does not include user accounts, cloud synchronization, or online database storage.
