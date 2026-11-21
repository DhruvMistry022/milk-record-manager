# Milk Record Manager

A responsive household milk tracking website built with plain HTML, CSS and JavaScript.

## Files
- `index.html` – page structure
- `style.css` – responsive layout and themes
- `script.js` – calculations, records, reports, CSV and backup features

## Run on a computer
1. Extract the ZIP file.
2. Open the `milk_record_manager` folder.
3. Double-click `index.html`, or right-click and open it in Chrome, Edge or Firefox.

No installation, server, PHP or database is required.

## Run on Android
1. Extract the ZIP using your phone's Files app.
2. Open the extracted folder.
3. Tap `index.html` and choose Chrome or another browser.
4. If your file manager does not open local HTML properly, upload the three website files to GitHub Pages or another static website host, then open the published HTTPS link.

## How to use
1. Open **Add record**.
2. Choose the date.
3. Enter morning and evening milk quantities in litres.
4. Enter the price per litre in rupees.
5. Choose Paid or Pending and optionally add a note.
6. Save. The daily total and amount are calculated automatically.
7. Choose a month on the dashboard or reports page to see that month's total.

## Important data note
Records are stored in LocalStorage in the browser on the device where you use the website. They do not automatically sync between phones or computers. Use **Backup & settings → Download backup** regularly. Keep the JSON backup somewhere safe. Restore it using **Choose backup file**.

A single record per date is supported. If you save another entry for the same date, the website asks whether you want to replace the existing record.
