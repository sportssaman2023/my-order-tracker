# My Order Tracker – Version 9 Courier Checker

## What's new
- Courier tab for Professional Courier, Shree Anjani, Shree Tirupati, DTDC, Shree Maruti and Shree Mahavir.
- Default pickup PIN 382424, editable and saved locally on this iPhone.
- Destination PIN entry and official courier lookup links.
- Manual verification log saved locally, with result categories distinguishing confirmed delivery coverage from a branch-only result.

## Important limitations
This is a safe link-out/manual-verification implementation. It does not scrape courier websites or claim live serviceability. Publicly visible branch/network finders are not necessarily delivery-serviceability APIs. Automated results require documented API access or written permission and secure server-side credentials. GitHub Pages is static hosting; never put courier API secrets in index.html.

## Publish
Upload all six files in this folder to the root of the GitHub Pages repository, replacing previous versions. Keep an exported CSV backup of orders first. Existing order data key remains `sports-saman-order-tracker-v3`; pickup PIN and verification notes use separate local keys.
