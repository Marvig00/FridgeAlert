# FridgeAlert 🥬

**Live demo:** https://marvig00.github.io/FridgeAlert/

## About the application

FridgeAlert is a web application designed to help people reduce food waste by keeping track of the food they have at home.

The application provides an overview of registered food products and helps users remember which items they should check soon.

## Features

- **Food inventory:** Add food products and view them in one place. Search, filter by status, edit items and mark them as used.
- **Estimated reminders:** Receive suggested reminder dates based on the type of product.
- **Editable dates:** Change suggested dates to suit your needs.
- **Learning from corrections:** When you correct a suggested date, FridgeAlert remembers it and suggests the same number of days the next time you add a product with that name.
- **Receipt scanning:** Attempt to identify food products from a receipt image and review the results before adding them. Text recognition runs in the browser (Tesseract.js).
- **Barcode lookup:** Type a barcode, or scan it with the camera in supported browsers, to look up the product name in the open Open Food Facts database.

## Technologies

- HTML
- CSS
- JavaScript
- Tesseract.js (receipt text recognition)
- Open Food Facts API (barcode lookup)

## How to use

1. Open FridgeAlert in a web browser.
2. Add a food product manually, look up a barcode or try the receipt-scanning feature.
3. Review the suggested reminder date.
4. Adjust the date if necessary.
5. Save the product and view it in your inventory.

## Privacy

FridgeAlert has no user accounts and no server. Everything you register is stored only in your own browser (localStorage) on your device. Receipt images are processed in the browser and are not uploaded.

## Important information

Reminder dates are estimates, not guarantees of food safety or actual expiry dates. Always check the product packaging and follow the stated storage instructions.

Receipt scanning may not identify every product correctly. Users should review detected products before saving them.

Camera barcode scanning requires HTTPS and a browser that supports the BarcodeDetector API. If it is not supported, the barcode can be typed in manually.

## Purpose

The purpose of FridgeAlert is to make food management easier and encourage people to reduce unnecessary food waste.

## AI-assisted development

ChatGPT was used to help brainstorm the application idea, generate and improve code, and develop the application's features.
Claude was used to review and fix bugs (Norwegian letters æ/ø/å in product names, receipt items being saved twice), test the application and record the demo video.
