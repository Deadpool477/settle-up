# Settle Up

Settle Up is a lightweight, single-page web application that helps groups split shared bills and calculates the minimum number of payments required to settle all debts.

## Features
* **Basic Mode:** Quickly split a total bill equally among a group of people.
* **Advanced Mode:** Assign specific weights (percentages) to individuals based on their share of the bill.
* **Exclusions:** Exclude specific members from the final split calculation if they do not need to pay or be paid further.
* **Payment Optimization:** Automatically calculates who owes whom and minimizes the total number of transactions required to settle up.
* **Export to Image/PDF:** Save the final ledger and transaction list as a PNG or PDF file to easily share with the group.
* **Dark Mode Support:** Automatically adapts to your device's light or dark theme preferences.

## Usage
Because Settle Up is a completely self-contained application, there is no installation or server setup required.

1. Download or clone the repository.
2. Open the `Settle Up.html` (or `index.html` if renamed for hosting) file directly in any modern web browser.
3. Select your mode (Basic or Advanced) and enter the number of people.
4. Input the names and the amount each person spent.
5. Click "Calculate split" to view the optimized payment transactions.

## Technologies Used
* HTML5 / CSS3 / Vanilla JavaScript
* [html2canvas](https://html2canvas.hertzen.com/) (loaded via CDN for image export)
* [jsPDF](https://parall.ax/products/jspdf) (loaded via CDN for PDF export)
