---
tags:
  - recording
aliases:
  - Perpetual Method
---
## Definition
The perpetual inventory system keeps detailed, continuous records of the sale and cost of each [[Inventory|inventory]] movement into and out of the business. The inventory on hand and the [[Cost of Sales|cost of sales]] are available at any time during the financial year.

It is one of the two methods of accounting for inventory (see [[Inventory#Accounting for Inventory]]), and the only one used in MPP1020.

## Features
- **At the point of purchase:** the purchase of inventory is treated as an asset held. The Inventory account then works as a **control account**, tracking all inventory that should be on hand.
- **At the point of sale:** both the selling price and the cost price (COGS) of each sale are recorded.
- **Stocktake:** because each item has detailed records, a [[Stocktake|stocktake]] confirms any individual inventory discrepancy (gain or loss).

## Double-Entry
Each transaction is recorded in the [[General Journal]] and posted to the [[General Ledger]] using the [[Debit and Credit#Rules of Debit and Credit|rules of debit and credit]].

### Inventory Purchases
When a business purchases inventory:
- Inventory (asset) increases.
- Accounts Payable (liability) increases if bought on credit, **or** Cash (asset) decreases if paid immediately.

### Purchase Returns & Allowances
- A **purchase return** is the return of goods to the supplier. The business receives a refund as either credit or cash.
- A **purchase allowance** occurs when the business keeps the goods and is granted a reduction in price.

When a business returns inventory to the supplier:
- Inventory (asset) decreases.
- Accounts Payable (liability) decreases if bought on credit, **or** Cash (asset) increases if paid at purchase.

### Payment to Accounts Payable (Creditors)
After buying inventory on credit, the business eventually settles the liability by paying the creditor.
- Adjust for any purchase returns before payment.
- The payment may be made with or without a discount, depending on the seller's [[Transaction#Credit Terms|credit terms]].

When a business pays accounts payable:
- Accounts Payable (liability) decreases.
- Cash (asset) decreases.
- Discount Revenue (income) increases, if the seller offers a discount.

### Inventory Sales
Every sale needs **two entries**:
1. **Selling price:** what the customer paid or owes the business.
2. **Cost price:** what the item originally cost the business to purchase.

The difference between the selling price and the cost price is the **gross profit** (or **mark-up**).

### Sales Returns
A **sales return** is the return of goods by the customer. The customer receives a refund as either credit or cash.

Like a sale, a sales return needs **two entries**: one for the selling price (what the business refunds the customer) and one for the cost price. Together they reverse the effects of the original sale.

### Receipt from Accounts Receivable (Debtors)
When a customer pays their outstanding balance, the business receives cash and reduces Accounts Receivable.
- Adjust for any sales returns before receipt.
- If early payment terms are offered, a discount may apply. See [[Transaction#Credit Terms|credit terms]].

When a business receives from accounts receivable:
- Cash (asset) increases.
- Accounts Receivable (asset) decreases.
- Discount Expense (expense) increases, if the business (as seller) offers a discount.

## Summary of Double Entries
### Buying Inventory
| Transaction                             | Debit (Dr)       | Credit (Cr)              |
| --------------------------------------- | ---------------- | ------------------------ |
| Buy inventory for cash                  | Inventory        | Cash                     |
| Buy inventory on credit                 | Inventory        | Accounts Payable         |
| Return inventory bought for cash        | Cash             | Inventory                |
| Return inventory bought on credit       | Accounts Payable | Inventory                |
| Pay accounts payable (without discount) | Accounts Payable | Cash                     |
| Pay accounts payable (with discount)    | Accounts Payable | Cash<br>Discount Revenue |

### Selling Inventory
| Transaction                                         | Entry         | Debit (Dr)               | Credit (Cr)         |
| --------------------------------------------------- | ------------- | ------------------------ | ------------------- |
| Sell inventory for cash                             | Selling price | Cash                     | Sales Income        |
|                                                     | Cost price    | Cost of Sales            | Inventory           |
| Sell inventory on credit                            | Selling price | Accounts Receivable      | Sales Income        |
|                                                     | Cost price    | Cost of Sales            | Inventory           |
| Customer returns inventory sold for cash            | Selling price | Sales Return             | Cash                |
|                                                     | Cost price    | Inventory                | Cost of Sales       |
| Customer returns inventory sold on credit           | Selling price | Sales Return             | Accounts Receivable |
|                                                     | Cost price    | Inventory                | Cost of Sales       |
| Receive from accounts receivable (without discount) |               | Cash                     | Accounts Receivable |
| Receive from accounts receivable (with discount)    |               | Cash<br>Discount Expense | Accounts Receivable |
