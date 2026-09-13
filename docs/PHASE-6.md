# Phase 6 — Purchasing, Inventory & Material Costing

## Workflow
Supplier -> Purchase Order -> Receive -> Inventory IN -> Average Cost -> Issue to Project -> Inventory OUT -> Project Material Cost.

## Features
- Supplier records and supplier balance.
- Purchase orders with VAT and line items.
- Purchase order receiving.
- Inventory items with SKU, unit, minimum stock, location and average cost.
- Stock IN and OUT movements.
- Insufficient-stock protection.
- Project material issue with automatic costing using current weighted average cost.
- Project material-cost endpoint.
- Supplier payments.

## Important rule
A material issued to a project is recorded as a direct project cost. Stock quantity decreases at the same time. Purchased quantities update the item's weighted average cost.

## Next
Phase 7 should add polished UI screens, document/PDF printing, audit trail, backups, permissions and deployment.