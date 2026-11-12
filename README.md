# Print Ledger

Mobile-first 3D-printing stock and profitability tracker in Australian dollars.

## Features
- Product catalogue with repeatable print models
- Filament spool inventory, material price per gram and consumption
- Print jobs with quantities, failed prints, electricity and machine-wear estimates
- Sales with product quantities, discounts, postage, platform fees and estimated cost of goods
- Revenue, operating profit, stock remaining and filament usage dashboard
- Export sales CSV and export/import full JSON backups
- Installable mobile web app (PWA manifest)

## Run & deploy

No build tools required. The application uses plain HTML, CSS and JavaScript. Connect the GitHub repository to Vercel, choose the **Other** framework preset and deploy the repository root.

## Data and important limitations

Records currently live in **localStorage for this browser only**, not in cloud storage. Data will not sync between phones and computers. Keep regular backups using **Settings → Export backup**. Clearing browser storage may permanently erase records without a backup.

This version tracks one filament spool per print job. Automatic Bambu Studio sync, multiple spool consumption per print job, authentication, shared cloud storage, product image uploads, purchase order management and comprehensive tax reporting are not yet implemented.

Operating profit is an estimate, before income tax. The app is not a replacement for financial records or professional accounting advice.
