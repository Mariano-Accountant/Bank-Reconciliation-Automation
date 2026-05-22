# Overview

Automated bank reconciliation workflow built with Power Query in Excel 365.

Cleans raw bank and GL data, standardizes transaction formats, and automatically identifies matched and unmatched entries using date and amount logic.

## Features

- Automated data cleaning and standardization
- Debit/credit normalization into single signed amount
- Full outer joins and anti-join logic
- Refresh-based reconciliation workflow
- Exception reporting for unmatched transactions

## Sheets

| Sheet | Purpose |
|-------|---------|
| Bank statement | RAW input — paste bank export here |
| GL — Acc. 572 | RAW input — paste ledger export here |
| Bank_reconciliation | Full outer join — all transactions |
| Entries in bank NOT in GL | Items to post in accounting |
| Entries in GL NOT in bank | Items to investigate |

## Tech stack

Excel 365 · Power Query

## Result

Reduced manual reconciliation time from hours to a fast refresh-driven process

## Author

Mariano Jacquet — [LinkedIn](https://www.linkedin.com/in/marianoaccountant/)
