---
tags:
  - recording/adjustment
aliases:
  - Prepaid Expense
  - Prepaid Insurance
  - Prepaid Rent
  - Asset Method
  - Expense Method
---
## Definition
**Prepaid expenses** are payments made in advance for goods or services to be received in the future. Examples include prepaid rent, insurance and subscriptions.

They are one of the [[Balance Day Adjustments|balance day adjustments]].
- They are often (but not always) recorded as an [[Assets|asset]], to show the economic resource that exists when the cash is paid (consistent with accrual accounting).
- To the extent the expenditure has been consumed (incurred), it is expensed to the relevant [[Expense|expense]] account, e.g. Rent Expense.

## Why the Adjustment Is Needed
Under accrual accounting, at the end of the accounting period the business records:
- the portion **used up** as an expense, so the expense is recognised in the period it is incurred ([[Income Statement|income statement]])
- the portion **still prepaid** as an asset (current asset in the [[Balance Sheet|balance sheet]])

## Recording Methods
When a business initially pays an expense in advance, it can choose to record it either as an asset or as an expense, depending on the method used.

|                        | Asset Method                                                                                   | Expense Method                                          |
| ---------------------- | ---------------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| Initial recording      | Prepaid expense is recorded as an asset (e.g. Prepaid Rent). Reflects future economic benefit. | The entire payment is initially recorded as an expense. |
| Initial entry          | Dr Prepaid Expense<br>Cr Cash/Bank                                                             | Dr Expense<br>Cr Cash/Bank                              |
| Balance day adjustment | Dr Expense<br>Cr Prepaid Expense                                                               | Dr Prepaid Expense<br>Cr Expense                        |

### Asset Method
**Initial entry:** when a prepaid expense is incurred, it is recorded as an asset because it represents a future economic benefit. This is done at the time of payment.

| Details/Accounts | Debit (Dr) | Credit (Cr) |
| --- | --: | --: |
| Prepaid Expense *(asset increase)* | Amount | |
| &emsp;Cash *(asset decrease)* | | Amount |

**Adjusting entry:** at the end of the accounting period, the portion of the prepaid expense that has been used up is transferred from the asset account to an expense account. This ensures that the expense is recognised in the period it is incurred.

| Details/Accounts | Debit (Dr) | Credit (Cr) |
| --- | --: | --: |
| Expense *(expense increase)* | Amount | |
| &emsp;Prepaid Expense *(asset decrease)* | | Amount |

### Expense Method
**Initial entry:** when a prepaid expense is incurred, it is recorded directly as an expense. This method assumes that the entire payment is an expense at the time of payment.

| Details/Accounts | Debit (Dr) | Credit (Cr) |
| --- | --: | --: |
| Expense *(expense increase)* | Amount | |
| &emsp;Cash *(asset decrease)* | | Amount |

**Adjusting entry:** at the end of the accounting period, the portion of the prepaid expense that has not been used up is transferred from the expense account to an asset account. This ensures that the unused portion is recognised as an asset.

| Details/Accounts | Debit (Dr) | Credit (Cr) |
| --- | --: | --: |
| Prepaid Expense *(asset increase)* | Amount | |
| &emsp;Expense *(expense decrease)* | | Amount |

## Example
**Scenario:** Green Tech Solutions paid $1,200 in advance on 1 January 2025 for a one-year (12 months) insurance policy. The end of the period adjustment is required on 30 June 2025.

Under accrual accounting, the business should record 6 months of insurance expense at the end of the accounting period, and show that 6 months are still prepaid (an asset).

| Period | Months | Amount | |
| --- | --: | --: | --- |
| 1 Jan – 30 Jun 2025 | 6 | $600 | Insurance consumed (expense) |
| 1 Jul – 31 Dec 2025 | 6 | $600 | Still prepaid (asset) |

$$
\frac{1{,}200}{12} = 100 \times 6 = \$600
$$

### Asset Method
**General Journal**

| Date        | Details/Accounts                                                     | Debit (Dr) | Credit (Cr) |
| ----------- | -------------------------------------------------------------------- | ---------: | ----------: |
| 1 Jan 2025  | Prepaid Insurance                                                    |      1,200 |             |
|             | &emsp;Cash                                                           |            |       1,200 |
| 30 Jun 2025 | Insurance Expense                                                    |        600 |             |
|             | &emsp;Prepaid Insurance                                              |            |         600 |
|             | *(1,200/12 = 100 × 6 = 600: insurance used from January to June)*    |            |             |

**General Ledger: Prepaid Insurance**

| Date       | Details |    Dr | Date        | Details           |  Cr |
| ---------- | ------- | ----: | ----------- | ----------------- | --: |
| 1 Jan 2025 | Cash    | 1,200 | 30 Jun 2025 | Insurance Expense | 600 |

**General Ledger: Insurance Expense**

| Date        | Details           |  Dr | Date | Details | Cr |
| ----------- | ----------------- | --: | ---- | ------- | -: |
| 30 Jun 2025 | Prepaid Insurance | 600 |      |         |    |

### Expense Method
**General Journal**

| Date        | Details/Accounts                                                     | Debit (Dr) | Credit (Cr) |
| ----------- | -------------------------------------------------------------------- | ---------: | ----------: |
| 1 Jan 2025  | Insurance Expense                                                    |      1,200 |             |
|             | &emsp;Cash                                                           |            |       1,200 |
| 30 Jun 2025 | Prepaid Insurance                                                    |        600 |             |
|             | &emsp;Insurance Expense                                              |            |         600 |
|             | *(1,200/12 = 100 × 6 = 600: paid in advance for July to December)*  |            |             |

**General Ledger: Insurance Expense**

| Date       | Details |    Dr | Date        | Details           |  Cr |
| ---------- | ------- | ----: | ----------- | ----------------- | --: |
| 1 Jan 2025 | Cash    | 1,200 | 30 Jun 2025 | Prepaid Insurance | 600 |

**General Ledger: Prepaid Insurance**

| Date        | Details           |  Dr | Date | Details | Cr |
| ----------- | ----------------- | --: | ---- | ------- | -: |
| 30 Jun 2025 | Insurance Expense | 600 |      |         |    |

### Report Extract
The extract is the same under both methods.

**Green Tech Solutions: extract of the reports for the year 2025**

| Income Statement | |
| --- | --: |
| Insurance expense | 600 |
| **Balance Sheet: Current Assets** | |
| Prepaid insurance | 600 |

## If Not Recorded
| Statement | Asset method | Expense method |
| --- | --- | --- |
| Income Statement | Expenses understated, so profit overstated | Expenses overstated, so profit understated |
| Statement of Changes in Equity | Equity overstated | Equity understated |
| Balance Sheet | Assets overstated, equity overstated | Assets understated, equity understated |
| Statement of Cash Flows | No effect | No effect |
