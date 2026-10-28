# Profit and Loss Statement: layout

Use this layout for every monthly, quarterly, and annual P&L. Build it as a spreadsheet (.xlsx) with live formulas for every total, not typed-in numbers, so the owner and their accountant can check the math. If the rulebook asks for a PDF too, export the same sheet.

## Workbook

**Sheet 1 — "Profit and Loss"**

Header rows:
- {{BUSINESS LEGAL NAME}}
- Profit and Loss Statement
- {{Month YYYY}} (or {{Qn YYYY}}, or {{Year YYYY}})
- Basis: Cash

(Cash basis means income and expenses are counted when the money actually moved. Print just "Basis: Cash" on the statement. Use "Basis: Accrual" only if the rulebook says the accountant keeps the books that way.)

Columns:
| Line | This period | Year to date | Same period last year | Change vs. last year |
|---|---|---|---|---|

Leave "Same period last year" blank, not zero, and add a note, when there's no data for it yet.
If earlier months of the year haven't been uploaded, the year-to-date column covers only the months on file. Label its header "Since {{first month on file}}", not "Year to date", and add a note.

Rows, in this order:

**INCOME**
- one row per income category from the rulebook
- **Total income** = sum of income rows

**COST OF SERVICES** (skip the whole section if the rulebook says "none")
- one row per cost-of-services category
- **Total cost of services**
- **Gross profit** = total income − total cost of services

**EXPENSES**
- one row per expense category, in the rulebook's order
- **Total expenses**

**NET PROFIT** = gross profit (or total income, if there's no cost of services section) − total expenses
- **Profit margin** = net profit ÷ total income, shown as a percent

Notes block under the statement:
- uncategorized items still waiting on the owner (count and total), if any
- possible personal charges excluded from the statement (count and total)
- any account or month with missing data
- "Prepared from your records by your AI Finance Assistant. Not reviewed by a CPA."

**Sheet 2 — "Transactions"**
| Date | Account (last 4) | Description | Category | Amount | Receipt? | Notes |
Income is positive, expenses are negative. Sort by date.

**Sheet 3 — "Unpaid Invoices"**
| Client | Invoice # | Amount | Date sent | Due date | Days past due |

## Rules
- Totals use formulas, never typed numbers.
- Transfers between the owner's own business accounts aren't income or expenses. Leave them out of the P&L, and list them on the Transactions sheet with the category "Transfer".
- Owner's draws or personal payments aren't business expenses. Use the category "Owner draw / personal" and leave them off the P&L.
- Payments toward a business credit card aren't expenses (the card's charges are). Treat the payment as a "Transfer".
- If payment-platform payout reports were uploaded, record the full sale as income and the platform fee under "bank and payment processing fees". If only bank deposits are available, record the deposit and add the note "Income shown after payment platform fees."
- Loan proceeds aren't income. If you're unsure how to treat a loan payment or a large equipment purchase, list it under "Questions for your accountant" instead of guessing.
- Amounts are rounded to cents. Totals are never rounded to hide gaps.
