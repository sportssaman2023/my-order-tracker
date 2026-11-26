# My Order Tracker — iPhone PWA edition

This is a browser-based installable app intended for Safari on iPhone.

## Features
- Manual order entry, editing and deletion
- Personal and Business classification
- INR currency display
- Order status, platform and payment method
- Dashboard with total orders, value, delivered, pending and this-month totals
- Search and filters
- Monthly, yearly, platform-wise and product-wise reports
- CSV export for Excel/Numbers
- Print-to-PDF using Safari's Share/Print flow
- Light/dark appearance follows the device
- Local browser storage and offline shell caching after first successful load

## Important privacy and storage note
Order records are stored in this browser's localStorage on this iPhone. They are not uploaded to a database by this app. Browser storage is not a guaranteed backup: clearing Safari website data, deleting site data, or removing the installed web app may erase records. Export CSV regularly.

## Install on iPhone
A PWA must be served from a secure HTTPS website for Home Screen installation and service-worker offline support. The ZIP itself cannot be installed directly.
1. Host the contents of this folder at an HTTPS address using a static hosting service.
2. Open that HTTPS address in Safari on your iPhone.
3. Tap Share → Add to Home Screen → Add.
4. Launch the new Home Screen icon. Add a test order and check it remains after closing/reopening.
5. Export a CSV backup periodically.

## Hosting from an iPhone
A static host such as GitHub Pages can serve these files, but account creation and repository setup are required. Keep the repository private if you prefer not to expose source code; note that private repository Pages availability depends on the hosting plan. Do not put actual order records in the repository—the app stores them locally in the browser.

This is a starter PWA package, not a hosted URL or native App Store binary.
