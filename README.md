# Fresh Market Wholesale — improved PWA

Responsive English/Khmer vegetable wholesale demo for desktop and mobile. Includes real-photo vegetable cards, farm/farmer photography, shopping cart, customer checkout, seller dashboard, inventory management, customer list, order status updates, CSV export, and installable PWA support.

## Run on Windows
1. Extract this ZIP.
2. Open the extracted `fresh-market-wholesale-pwa` folder in VS Code.
3. Install the **Live Server** extension.
4. Right-click `index.html` → **Open with Live Server**.
5. Keep internet connected to load the farm and vegetable photographs.

## Install on a phone
Deploy the folder to an HTTPS host such as GitHub Pages, Netlify, or Vercel. Open the deployed website in Chrome/Edge and choose **Install app**. On iPhone Safari use Share → Add to Home Screen.

## Test the app
- Customer: browse/search/filter vegetables, add quantities in kg, fill name/phone/address, and place an order.
- Seller: click the role switch to open Dashboard, Inventory, and Customers. Review order details, change order status, update stock/prices, and export CSV.
- Switch English/Khmer from the top-right language selector.

## Important limitations before real business use
This is a front-end prototype. Orders and inventory are stored in the browser's localStorage on the device that created them. It does not yet sync customer orders to a seller's separate phone or send Telegram/email alerts. The role switch is a demo, not secure seller authentication. Real multi-device use requires a shared backend/database, secure login, and notification integration (for example Supabase/Firebase plus an email/Telegram service). Prices and stock are sample data; update them before selling.

## Photos
Vegetable and farm photographs are loaded from Unsplash URLs and therefore need an internet connection. The app itself can open offline after it has been cached, but remote photos may not appear offline.
