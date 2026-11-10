SHREYASH MACHINERY & HARDWARE — EXISTING APP + IMPORT EXCEL ONLY

This package keeps the existing V3.1 app design and existing app features.
Only the Customers page has been changed: the old fixed contact import option
is replaced with an "Import Excel" button.

Supported files: .xlsx, .xls, .csv
Required column: Name
Optional columns: Contact Number-1, Contact Number-2, Address
Common alternate column headings are also accepted.

How to install:
1. Keep a backup of your current GitHub repository.
2. Replace only index.html in your existing GitHub repository with this index.html.
3. Commit and wait for GitHub Pages to publish.
4. Open your existing app URL > Customers > Import Excel.
5. Select the workbook and confirm the number of new customers.
6. Existing customers are skipped by matching name or primary phone number.

The existing app's rental, return-day calculation, editable bill amount, invoices,
payments, reports, login and existing cloud connection are retained.
The Excel file is read in the browser; the import uses the app's existing data/cloud
save mechanism. No Supabase setup or new database is required for this change.
