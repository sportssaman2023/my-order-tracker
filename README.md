# My Order Tracker V3 — Sports Samaan label maker

## What's new
- Paste address messages using fields such as Name, Address, Landmark, PIN code, City, State, Mobile, Email and Size.
- Extract labelled fields automatically, then review/edit them.
- Preview and print the supplied Sports Samaan label template.
- Save recipient details and order data locally in this iPhone browser.
- Track order statuses, count labels/orders and view yearly monthly counts, city-wise and size-wise reports.
- Export order data as CSV for Excel/Numbers.
- Offline app shell and local browser storage.

## Deploy update to existing GitHub Pages repository
Upload/replace these files at the root of your existing repository:
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- label-template.jpg

Commit changes to `main`. GitHub Pages should redeploy automatically. Existing app may need a refresh/reopen to load the new version. The service worker cache name has been incremented for V3.

## Printing
Print layout is configured for portrait 4 x 6 inch paper. Confirm printer support and test on ordinary paper first. The supplied label image is used as the fixed background; extracted recipient fields are overlaid in the recipient area. Check alignment and field wrapping on a test print before using label stock.

## Important parser limitations
Address parsing is based on field labels and simple text matching, not AI. It works best when pasted text uses one field per line in a format like:
Name - ...
Address - ...
Landmark - ...
Pin code - ...
City - ...
State - ...
Mobile - ...
Email - ...
Size - ...

Always review and correct extracted fields before saving/printing. If the customer sends an unlabelled or differently formatted address, some fields may need manual correction.

## Privacy and data safety
Order records stay in this browser's localStorage; the app does not upload them to GitHub. GitHub contains the public app source and label template only. Export CSV backups regularly. Clearing Safari site data or removing the app may erase local records.


Label typography update: all recipient value fields use a consistent 26px base size at the original 853px template width (equivalent scaled size in preview/4×6 print). Long values automatically reduce only when required to fit the available line. The label background logo now reads SPORTS SAMAAN. Recipient overlay positions were tuned to keep text aligned with the printed labels and clear of the horizontal rules.
