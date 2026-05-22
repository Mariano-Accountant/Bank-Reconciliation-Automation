# Bank reconciliation automation

Automated bank reconciliation template built with Power Query in Excel.

Paste raw data, refresh all queries, and instantly identify matched and unmatched transactions.

## Features

- Automated data cleaning
- Debit/credit normalization
- Date format standardization
- Full outer joins and anti-joins
- Exception reporting for unmatched entries
- Refresh-based monthly workflow

## Sheets

| Sheet | Purpose |
|-------|---------|
| Bank statement | RAW input — paste bank export here |
| GL — Acc. 572 | RAW input — paste ledger export here |
| Bank_reconciliation | Full outer join — all transactions |
| Entries in bank NOT in GL | Items to post in accounting |
| Entries in GL NOT in bank | Items to investigate |

## Power Query transformations

- Remove metadata rows
- Trim and clean text fields
- Standardize date formats
- Convert debit/credit into signed amounts
- Filter summary rows
- Merge queries using date + amount logic
- Generate anti-join exception reports

## Tech stack

Excel 365 · Power Query

## Monthly workflow

- Paste the latest bank statement export
- Paste the latest GL export
- Refresh all queries
- Review unmatched transactions
- Post adjustments if needed
- Refresh again

## Author

Mariano Jacquet — [LinkedIn](https://www.linkedin.com/in/marianoaccountant/)
