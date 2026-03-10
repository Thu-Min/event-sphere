---
id: F-011
title: Stripe checkout integration
status: unassigned
milestone: M4
branch: feature/stripe-checkout
issue: 11
dependsOn:
  - F-003
  - F-010
---

## Acceptance Criteria

- [ ] Stripe SDK integrated on backend
- [ ] POST /api/orders creates a Stripe checkout session
- [ ] User selects ticket type and quantity, then redirected to Stripe
- [ ] Webhook receives payment confirmation from Stripe
- [ ] Order record created with status tracking (pending, paid, failed)
- [ ] Handles Stripe test mode for development
