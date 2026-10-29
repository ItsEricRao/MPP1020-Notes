---
tags:
  - recording
aliases:
  - Inventory Loss
  - Inventory Gain
---
## Definition
A **stocktake** is a manual count of the physical [[Inventory|inventory]] on hand.

The [[Perpetual Inventory System|perpetual inventory system]] keeps a continuous record of inventory movements in the Inventory ledger, but the balance should still be verified at least annually with a stocktake. At period end, the recorded balance (in the [[General Ledger|ledger]]) is cross-checked against the actual balance for each individual item of inventory.

A stocktake may:
- confirm the inventory balance is correct,
- identify that inventory is missing (an **inventory loss**), or
- identify more inventory on hand than expected (an **inventory gain**).

## Inventory Loss
An **inventory loss** occurs when the actual balance is **less than** the recorded balance. It is an [[Expense|expense]].
$$
\text{Inventory Loss} = \text{Recorded Balance} - \text{Actual Balance}
$$

**Possible reasons**
- Undersupply by suppliers not detected
- Oversupply to customers
- Theft or shoplifting
- Incorrect recording in the inventory ledger (recording error)

**Journal entry**

| Details/Accounts | Debit (Dr) | Credit (Cr) |
| --- | --: | --: |
| Inventory Loss *(expense increase)* | Amount | |
| &emsp;Inventory *(asset decrease)* | | Amount |

## Inventory Gain
An **inventory gain** occurs when the actual balance is **more than** the recorded balance. It is [[Income|income]].
$$
\text{Inventory Gain} = \text{Actual Balance} - \text{Recorded Balance}
$$

**Possible reasons**
- Oversupply by suppliers
- Undersupply to customers
- Recording errors

**Journal entry**

| Details/Accounts | Debit (Dr) | Credit (Cr) |
| --- | --: | --: |
| Inventory *(asset increase)* | Amount | |
| &emsp;Inventory Gain *(income increase)* | | Amount |

After the loss or gain is posted, the closing balance of the Inventory ledger account equals the actual inventory on hand found by the stocktake.

> [!todo]
> Inventory loss and gain adjustments are covered again in week 5.
