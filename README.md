# PriykaStore Billing

A lightweight, mobile-first grocery billing starter for PriykaStore.

## Features
- Product-number and name search; tap a product to add it to the bill
- Starter catalogue with illustrative prices and **zero opening stock**
- Edit selling prices and stock quantities
- Cash, UPI, split payment and credit/due tracking
- Customer credit balances and payment collection
- Expense log
- CSV exports for bills, bill items, products/stock, credit and expenses
- JSON backup and restore
- Printable receipt (browser print dialog; Bluetooth thermal printer compatibility must be tested on the target Android device)
- Local browser storage and basic offline caching

## Publish with GitHub Pages
1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then press **Save**.
4. After deployment completes, open: https://duckgamer23.github.io/-billing/

## Important data warning
This starter stores sales, products, credit, and expenses in the browser's local storage. It does **not** currently sync between devices. Clearing browser data, using another browser/device, or losing the device can lose those records. Download a JSON backup regularly and keep it somewhere safe.

Before live shop use:
- Set the correct selling price for each product.
- Enter the real opening stock for each product; the starter sets it to zero.
- Test billing, credit collection, CSV export and receipt printing.
- Create a secure cloud database with authentication and per-user access policies before adding cross-device cloud sync. Do not put database passwords or service-role keys in website code.

Starter catalogue prices are illustrative examples only, not verified current market prices.
