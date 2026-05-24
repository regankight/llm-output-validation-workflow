# Invoice Intake Workflow

## Goal

Convert emailed invoices into structured records for downstream business systems.

## Workflow

Email received  
↓  
Invoice text extracted  
↓  
LLM generates structured invoice data  
↓  
Validation layer checks required fields  
↓  
If valid → save record  
↓  
If invalid → repair attempt  
↓  
If still invalid → human review queue

## Required Fields

- vendor name
- invoice number
- invoice date
- total amount
- currency
- due date

## Human Review Triggers

- missing required field
- multiple invoices detected
- conflicting totals
- malformed output
- unsupported invoice format
