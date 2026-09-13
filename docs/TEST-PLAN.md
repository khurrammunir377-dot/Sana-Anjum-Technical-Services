# Post-Phase-7 Test Plan

1. Fresh installation and database migration.
2. Create lead -> customer -> project.
3. Create quotation with multiple lines -> verify subtotal, 5% VAT and total.
4. Convert/record invoice -> receive partial and full payments -> verify receivable.
5. Create supplier -> purchase order -> receive -> verify stock and weighted average cost.
6. Issue material to project -> verify stock reduction and project material cost.
7. Add regular and daily workers -> verify labour cost.
8. Add project expenses -> verify actual project cost and margin.
9. Verify supplier balance and payments.
10. Verify VAT output/input reporting once purchase invoices are linked.
11. Verify low-stock and insufficient-stock warnings.
12. Print quotation and invoice; verify AED, VAT, customer and company details.
13. Verify responsive screens on desktop and phone widths.
14. Verify backup/restore and audit history.
15. Run TypeScript/build checks and API smoke tests.
