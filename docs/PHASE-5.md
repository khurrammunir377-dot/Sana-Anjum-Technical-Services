# Phase 5 — Documents, VAT & Management Reporting

Phase 5 extends Phases 1–4 without adding a customer portal.

## Scope
- Quotation line items: description, quantity, unit, rate, amount.
- Automatic quotation subtotal, VAT and grand total.
- Invoice line items with the same calculation rules.
- Professional printable quotation/invoice document views (browser print to PDF).
- Customer payment allocation to invoices: Paid / Partially Paid / Outstanding.
- Supplier payment records and outstanding balance foundation.
- Cash/bank accounts and cash transactions.
- Finance summary: invoiced, received, receivable, expenses, labour and operating result.
- Project profitability report with contract value, direct cost, profit and margin.
- VAT summary: output VAT, input VAT and net VAT payable/credit. Input VAT is completed when supplier purchase invoices are linked in the purchasing module.

## Business rule
All monetary calculations are stored in AED. Default VAT rate is 5% but must remain configurable in settings. Do not hard-code VAT into historical records.

## Document rule
Documents must show company name, Dubai address, customer details, TRN when available, document number/date, line items, subtotal, VAT and grand total. Never expose internal notes on customer-facing documents.

## Next
Phase 6 will complete purchasing/inventory costing, supplier balances, material issue costing and management reports.