# Payment Reconciliation Tracker | Veriton Bank
**Tool:** Microsoft Excel | **Duration:** March 2025 | **Domain:** Banking Operations
 
---
 
## Overview
 
This project simulates an end-to-end payment reconciliation system for a retail bank processing incoming customer deposits. It replicates a core daily banking operations task — matching incoming payments against expected records, flagging exceptions, and producing a structured reconciliation report for the operations team.
 
---
 
## Business Problem
 
Retail banks receive hundreds of incoming payments daily via multiple channels (CHAPS, BACS, Faster Payments, Online Transfer, Cheque). Without a structured reconciliation system, unmatched payments, missing references, and duplicate entries go undetected — creating financial risk and compliance issues. This tracker was designed to address that gap.
 
---
 
## What the File Contains
 
**Sheet 1 — Bank Transactions**
A register of 50 simulated incoming payment transactions for March 2025, including transaction ID, date, customer name, account number, payment type, amount, reference number, and reconciliation status (Matched / Unmatched / Pending). Colour-coded status flags for instant visual triage.
 
**Sheet 2 — Expected Payments Ledger**
A parallel ledger of 45 expected incoming payments with a Days Overdue column that flags how many days each unmatched or pending payment has exceeded its due date. Enables prioritisation of follow-up actions.
 
**Sheet 3 — Reconciliation Summary**
A management-ready daily report featuring:
- KPI cards: Total Transactions, Total Amount (GBP), Matched, Unmatched, Pending, and Reconciliation Rate
- Breakdown table by payment type (CHAPS, BACS, Faster Payments, Online Transfer, Cheque) with match rates per channel
- Exception Log listing all unmatched and pending items with assigned officer, issue type, and resolution deadline
 
---
 
## Key Formulas Used
 
- COUNTIF / COUNTIFS — status counting and filtering by payment type and status
- SUMIF — total amount reconciled per payment channel
- IFERROR — handling zero-division cases in match rate calculations
- Conditional Formatting — automated green/amber/red status coding across all sheets
 
---
 
## Key Findings
 
- Reconciliation rate across 50 transactions: calculated dynamically in Sheet 3
- CHAPS and Faster Payments show the highest average transaction values
- 5 exception items identified requiring same-day resolution
- Cheque payments had the highest proportion of Pending status due to clearing delays
 
---
 
## Skills Demonstrated
 
Payment reconciliation | SLA-driven exception management | KPI reporting | Data validation | Financial record maintenance | MS Excel (COUNTIFS, SUMIF, IFERROR, Conditional Formatting)
 
---
 
## How to Use
 
1. Open the file in Microsoft Excel
2. Review Sheet 1 for the full transaction register
3. Check Sheet 2 for overdue expected payments (sorted by Days Overdue)
4. Go to Sheet 3 for the reconciliation summary and exception log
5. The KPI cards and breakdown table update automatically based on Sheet 1 data
   
