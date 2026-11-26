---
tags:
  - recording/adjustment
aliases:
  - Unearned Income
  - Unearned Revenue
  - Prepaid Revenue
  - Liability Method
  - Income Method
---
## Definition
**Prepaid income** refers to money a business receives for goods or services that have not yet been delivered or performed. Examples include advance payments for subscription services and rent received in advance.

It is also known as **prepaid revenue**, **unearned income** or **unearned revenue**.

It is one of the [[Balance Day Adjustments|balance day adjustments]].
- It is often (but not always) recorded as a [[Liabilities|liability]], to show the present obligation that exists when the cash is received (consistent with accrual accounting).
- It is moved to an [[Income|income]] account when the income is later earned.

## Why the Adjustment Is Needed
The adjustment ensures that:
- the income earned in the accounting period is recognised in the [[Income Statement|income statement]]
- the remaining unearned income is reported as a liability (current liability in the [[Balance Sheet|balance sheet]])

## Recording Methods
When a business initially receives income in advance, it can choose to record it either as a liability or as income, depending on the method used.

|                        | Liability Method                                                                                       | Income Method                                       |
| ---------------------- | ------------------------------------------------------------------------------------------------------ | --------------------------------------------------- |
| Initial recording      | Initially recorded as a liability (Prepaid Income). Reflects the obligation to deliver goods/services. | The entire payment is initially recorded as income. |
| Initial entry          | Dr Cash/Bank<br>Cr Prepaid Income                                                                      | Dr Cash/Bank<br>Cr Income                           |
| Balance day adjustment | Dr Prepaid Income<br>Cr Income                                                                         | Dr Income<br>Cr Prepaid Income                      |

### Liability Method
**Initial entry:** when prepaid income is received, it is recorded as a liability because the business has not yet earned the revenue.

| Details/Accounts | Debit (Dr) | Credit (Cr) |
| --- | --: | --: |
| Cash/Bank *(asset increase)* | Amount | |
| &emsp;Prepaid Income *(liability increase)*  | | Amount |

**Adjusting entry:** at the end of the accounting period, the portion of the prepaid income that has been earned is transferred from the liability account to a revenue account. This ensures that the revenue is recognised in the period it is earned.

| Details/Accounts | Debit (Dr) | Credit (Cr) |
| --- | --: | --: |
| Prepaid Income *(liability decrease)*  | Amount | |
| &emsp;Income *(income increase)* | | Amount |

### Income Method
**Initial entry:** when prepaid income is received, it is recorded as income.

| Details/Accounts | Debit (Dr) | Credit (Cr) |
| --- | --: | --: |
| Cash/Bank *(asset increase)* | Amount | |
| &emsp;Income *(income increase)* | | Amount |

**Adjusting entry:** at the end of the accounting period, the portion of the income not yet earned is transferred from the income account to the prepaid income (liability) account. This ensures that the revenue is recognised in the period it is earned.

| Details/Accounts | Debit (Dr) | Credit (Cr) |
| --- | --: | --: |
| Income *(income decrease)* | Amount | |
| &emsp;Prepaid Income *(liability increase)*  | | Amount |

## Example
**Scenario:** Green Tech Solutions received $12,000 in advance on 1 April 2025 for goods to be delivered over the next 12 months. As of 30 June 2025 (end of the financial year), three months' worth of goods had been delivered.

The adjustment ensures that the income earned from April to June is recognised in the income statement, and the remaining unearned income is reported as a liability in the balance sheet.

| Period | Months | Amount | |
| --- | --: | --: | --- |
| 1 Apr – 30 Jun 2025 | 3 | $3,000 | Income earned |
| 1 Jul 2025 – 31 Mar 2026 | 9 | $9,000 | Prepaid income, not yet earned |

$$
\frac{12{,}000}{12} = 1{,}000 \text{ per month}
$$

### Liability Method
**General Journal**

| Date        | Details/Accounts                                                        | Debit (Dr) | Credit (Cr) |
| ----------- | ----------------------------------------------------------------------- | ---------: | ----------: |
| 1 Apr 2025  | Cash                                                                    |     12,000 |             |
|             | &emsp;Prepaid Income                                                    |            |      12,000 |
| 30 Jun 2025 | Prepaid Income                                                          |      3,000 |             |
|             | &emsp;Sales Income                                                      |            |       3,000 |
|             | *(12,000/12 = 1,000 × 3 = 3,000: goods delivered April to June)*        |            |             |

**General Ledger: Prepaid Income**

| Date        | Details      |    Dr | Date       | Details |     Cr |
| ----------- | ------------ | ----: | ---------- | ------- | -----: |
| 30 Jun 2025 | Sales Income | 3,000 | 1 Apr 2025 | Cash    | 12,000 |

**General Ledger: Sales Income**

| Date | Details | Dr | Date        | Details         |    Cr |
| ---- | ------- | -: | ----------- | --------------- | ----: |
|      |         |    | 30 Jun 2025 | Prepaid Income  | 3,000 |

### Income Method
**General Journal**

| Date        | Details/Accounts                                                        | Debit (Dr) | Credit (Cr) |
| ----------- | ----------------------------------------------------------------------- | ---------: | ----------: |
| 1 Apr 2025  | Cash                                                                    |     12,000 |             |
|             | &emsp;Sales Income                                                      |            |      12,000 |
| 30 Jun 2025 | Sales Income                                                            |      9,000 |             |
|             | &emsp;Prepaid Income                                                    |            |       9,000 |
|             | *(12,000/12 = 1,000 × 9 = 9,000: goods not yet delivered)*              |            |             |

**General Ledger: Sales Income**

| Date        | Details         |    Dr | Date       | Details |     Cr |
| ----------- | --------------- | ----: | ---------- | ------- | -----: |
| 30 Jun 2025 | Prepaid Income  | 9,000 | 1 Apr 2025 | Cash    | 12,000 |

**General Ledger: Prepaid Income**

| Date | Details | Dr | Date        | Details      |    Cr |
| ---- | ------- | -: | ----------- | ------------ | ----: |
|      |         |    | 30 Jun 2025 | Sales Income | 9,000 |

### Report Extract
The extract is the same under both methods.

**Green Tech Solutions: extract of the reports for the year 2025**

| Income Statement | |
| --- | --: |
| Sales income | 3,000 |
| **Balance Sheet: Current Liabilities** | |
| Prepaid income  | 9,000 |

## If Not Recorded
| Statement | Liability method | Income method |
| --- | --- | --- |
| Income Statement | Income understated, so profit understated | Income overstated, so profit overstated |
| Statement of Changes in Equity | Equity understated | Equity overstated |
| Balance Sheet | Liabilities overstated, equity understated | Liabilities understated, equity overstated |
| Statement of Cash Flows | No effect | No effect |
