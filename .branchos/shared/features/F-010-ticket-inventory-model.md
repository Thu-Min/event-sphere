---
id: F-010
title: Ticket type & inventory model
status: unassigned
milestone: M4
branch: feature/ticket-inventory-model
issue: null
dependsOn:
  - F-004
---

## Acceptance Criteria

- [ ] Ticket types linked to events with: name, price, total quantity, sold count
- [ ] API endpoint returns available ticket types for an event
- [ ] Inventory decrements atomically on purchase (no overselling)
- [ ] Sold-out ticket types display as unavailable
- [ ] Unique ticket ID generated for each purchased ticket
