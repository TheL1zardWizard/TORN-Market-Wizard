# TORN Market Wizard

Conjured by: theL1zardWizard

Scans the Torn Item Market through the official Torn API and lists items you can buy from players and sell to a city vendor for a profit. **It advises; you place the buys.**

## Use it

Open `torn-market-wizard.html` in a normal browser tab (double-click it). Paste your Torn API key into the page (a Limited Access key is enough), tick "Remember key in this browser" if you want it kept, and press **Scan market**. No server and nothing to install.

- **Table:** sortable and filterable by item, vendor, type, profit and ROI, with a data-age column and a Verify & open button that re-checks the price before opening the market listing.
- **Watch mode:** keeps re-checking a hot list (about 40 items, one request per 0.7 s) and alerts on new profitable listings with a sound, the tab title, and a desktop notification.
- **Demo:** "Load demo data" shows the layout with fake data.

## Notes

- Network traffic goes only to `api.torn.com`. Your key is never stored in this file.
- Bazaar prices aren't available through the API, so only the Item Market is scanned.
- Profit = vendor price minus listing price; no fees are assumed. Try one cheap flip first to confirm the numbers.
- There is no auto-buy. Torn's rules don't allow automation, so you always click through yourself.
