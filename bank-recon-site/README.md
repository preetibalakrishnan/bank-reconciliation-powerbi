# Bank Reconciliation Dashboard (Power BI)

A Power BI project built to practise reconciliation and reporting skills. It compares a company's cash book with its bank statement and shows what needs attention.

**Project page:** https://github.com/preetibalakrishnan/bank-reconciliation-powerbi/

All data is fictitious and prepared for practice. No real company or bank data is used.

I learned this using online tutorials, and I used AI tools for guidance where I needed help.

## What it does

- Compares 1,500 cash book lines with 1,500 bank statement lines using the reference number
- Assigns each line one of six statuses: Perfect match, Date mismatch, Amount mismatch, Only in books, Only in bank, Potential duplicate
- Classifies small differences (up to 3 days or Rs 100) as within tolerance
- Presents summary cards, a status chart, a table of items requiring action, and a bank account filter

## Result

Of 1,607 lines, 1,174 matched perfectly (73.06%) and 433 require follow-up.

## Files

- `index.html` - project page
- `data/bank_recon_sample_data.xlsx` - practice data
- `report/BankRecon_Dashboard.pbix` - Power BI file
- `assets/` - dashboard screenshot and PDF

## Tools

Power BI, Power Query, DAX, Excel

## Planned improvements

- Add a reconciliation statement
- Allow tolerance limits to be adjusted on the report page
- Test with messier, more realistic data
- Build budget vs actuals and receivables / payables ageing dashboards
