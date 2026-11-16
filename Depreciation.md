---
tags:
  - recording
aliases:
  - Accumulated Depreciation
  - Carrying Amount
  - Written Down Value
---
## Definition
**Non-current assets** (NCA) are assets the entity expects to control for more than 12 months, to earn income and cash. See [[Assets#Current vs. Non-Current Assets]].
- A non-current asset is recorded at its **cost** when acquired. It cannot be recorded as an expense at acquisition.
- Its economic benefits are used up (consumed) over its useful life, so a portion of its cost is consumed each period.
- That portion is reported as an [[Expense|expense]] in each period of the asset's life. This is **depreciation**: the allocation of the cost of a non-current asset over its useful life.

Depreciation is one of the [[Balance Day Adjustments|balance day adjustments]]. Depreciation of property, plant and equipment is covered by [[GENERALLY ACCEPTED ACCOUNTING PRINCIPLES (GAAP)#Accounting Standards|AASB 116 Property, Plant & Equipment]].

## Key Terms
- **Cost:** the purchase price, plus any other costs incurred to bring the asset to its required location and make it ready for use.
- **Useful life:** the period over which the asset is expected to be available for use by the entity.
- **Residual value:** the estimated amount the entity would currently obtain from disposing of the asset, after deducting the estimated costs of disposal.
- **Accumulated depreciation:** the total depreciation written off from the date the asset came under the entity's control until now. It is a **contra-asset** account.
- **Carrying amount** (book value, written down value): the amount at which the asset is recognised after deducting accumulated depreciation and impairment losses. It is the unallocated (unused) cost to date.

$$
\text{Carrying Amount} = \text{Cost} - \text{Accumulated Depreciation}
$$

## Adjusting Entry
| Details/Accounts | Debit (Dr) | Credit (Cr) |
| --- | --: | --: |
| Depreciation Expense *(expense increase)* | Amount | |
| &emsp;Accumulated Depreciation of NCA *(contra-asset increase)* | | Amount |

- **Depreciation Expense** allocates the cost of the asset over its useful life.
- **Accumulated Depreciation** builds up the total depreciation charged against the asset since it was acquired. The asset account itself stays at cost.

Accumulated depreciation is a contra-asset, so it works the opposite way to a normal asset: it increases with a **credit** and has a credit normal balance. See [[Debit and Credit]].

## Depreciation Methods
An asset's usage can be calculated with:
1. Straight-line
2. Reducing balance
3. Units of production

MPP1020 covers only the straight-line and reducing balance methods.

### Straight-Line Method
Allocates an **equal** depreciation expense each year over the asset's useful life. Suits assets with a constant income-earning pattern, such as furniture and buildings.
$$
\text{Annual Depreciation} = \frac{\text{Cost} - \text{Residual Value}}{\text{Useful Life}}
$$
or, with a depreciation rate $r$:
$$
\text{Annual Depreciation} = r\% \times (\text{Cost} - \text{Residual Value})
$$

### Reducing Balance Method
Also called the **declining balance method**. Allocates a **higher** depreciation expense in the early years of the asset's useful life, decreasing over time. Suits assets that are used more, or contribute more revenue, early in their life, such as computers, software and technological equipment.
$$
\text{Depreciation} = \text{Rate}\% \times (\text{Cost} - \text{Accumulated Depreciation})
$$
which is the same as:
$$
\text{Depreciation} = \text{Rate}\% \times \text{Written Down Value}
$$
Unlike the straight-line method, residual value is not deducted, and the expense is recalculated each year from the falling written down value.

Also called the **declining balance method**. Allocates a **higher** depreciation expense in the early years of the asset's useful life, decreasing over time. Suits assets that are used more, or contribute more revenue, early in their life, such as computers, software and technological equipment.## Reporting
- **[[Income Statement]]:** depreciation expense is a **non-cash expense** that reduces net profit.
- **[[Balance Sheet]]:** the non-current asset is reported at cost, less accumulated depreciation, to give its carrying amount.

**Balance sheet extract**

| Non-Current Assets | |
| --- | --: |
| Asset (at cost) | Cost |
| Less: Accumulated Depreciation | (Amount) |
| Carrying amount | Cost − Accumulated Depreciation |

Accumulated depreciation grows each year, so the carrying amount falls each year.

## If Not Recorded
- **Income Statement:** expenses understated, so profit overstated.
- **Statement of Changes in Equity:** equity overstated.
- **Balance Sheet:** assets overstated and equity overstated.
- **Statement of Cash Flows:** no effect.
