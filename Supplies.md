---
tags:
  - recording/adjustment
aliases:
  - Supplies Expense
  - Supplies on Hand
---
## Definition
**Supplies** are short-term [[Assets|assets]] used in the daily operations of a business. They are **consumed rather than sold**, and are recorded as **current assets** until they are used.

Compare [[Inventory|inventory]], which is held for sale.

Common supplies include office stationery (pens, paper, ink, folders), packaging materials and cleaning products.

## Why the Adjustment Is Needed
- Supplies are **initially recorded as an asset** when purchased, because they have not yet been used (consumed).
- At the end of the period, the amount **used** is recorded as an [[Expense|expense]] (Supplies Expense).

This is one of the [[Balance Day Adjustments|balance day adjustments]].

## Formula
$$
\text{Supplies Expense} = \text{Opening Supplies} + \text{Purchases} - \text{Closing Supplies}
$$
Closing supplies are the supplies still on hand at the end of the period. The formula has the same structure as the [[Cost of Sales#Formula|cost of sales formula]].

## Adjusting Entry
| Details/Accounts | Debit (Dr) | Credit (Cr) |
| --- | --: | --: |
| Supplies Expense *(expense increase)* | Amount | |
| &emsp;Supplies on Hand *(asset decrease)* | | Amount |

After the adjustment, the Supplies on Hand balance equals the supplies still on hand.

## Example
**Scenario:** On 1 July 2024, a business had $2,000 of office supplies on hand. On 1 January 2025, it bought another $800 of stationery for cash. At the end of the financial year (30 June 2025), a physical count found $500 of supplies left.

### Calculation
$$
\text{Supplies Expense} = 2{,}000 + 800 - 500 = \$2{,}300
$$
$2,800 of supplies was available during the year, and $500 is left, so $2,300 was used.

### General Journal

| Date        | Details/Accounts                                    | Debit (Dr) | Credit (Cr) |
| ----------- | --------------------------------------------------- | ---------: | ----------: |
| 1 Jan 2025  | Supplies on Hand                                    |        800 |             |
|             | &emsp;Cash                                          |            |         800 |
|             | *(Purchase of stationery for cash)*                 |            |             |
| 30 Jun 2025 | Supplies Expense                                    |      2,300 |             |
|             | &emsp;Supplies on Hand                              |            |       2,300 |
|             | *(Balance day adjustment: supplies used this year)* |            |             |

The purchase is recorded as an asset, because the supplies have not been used yet. The expense is recorded only at balance day.

### General Ledger
**Supplies on Hand**

| Date        | Details          |        Dr | Date        | Details          |        Cr |
| ----------- | ---------------- | --------: | ----------- | ---------------- | --------: |
| 1 Jul 2024  | Balance b/d      |     2,000 | 30 Jun 2025 | Supplies Expense |     2,300 |
| 1 Jan 2025  | Cash             |       800 | 30 Jun 2025 | Balance c/d      |       500 |
|             |                  | **2,800** |             |                  | **2,800** |
| 1 Jul 2025  | Balance b/d      |       500 |             |                  |           |

**Supplies Expense**

| Date        | Details          |    Dr | Date | Details | Cr |
| ----------- | ---------------- | ----: | ---- | ------- | -: |
| 30 Jun 2025 | Supplies on Hand | 2,300 |      |         |    |

After the adjustment, Supplies on Hand carries down $500, the amount the physical count found. Supplies Expense shows the $2,300 used.

> [!warning] Common mistake
> The expense is the amount **used** ($2,300). It is not the amount left ($500) or the amount purchased ($800). The closing supplies are **subtracted** in the formula, not added.

## If Not Recorded
- **Income Statement:** expenses understated, so profit overstated.
- **Statement of Changes in Equity:** equity overstated.
- **Balance Sheet:** assets overstated and equity overstated.
- **Statement of Cash Flows:** no effect.
