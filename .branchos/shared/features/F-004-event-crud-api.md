---
id: F-004
title: Event CRUD API
status: unassigned
milestone: M2
branch: feature/event-crud-api
issue: 4
dependsOn:
  - F-002
---

## Acceptance Criteria

- [ ] POST /api/events creates a new event (organizer only)
- [ ] GET /api/events/:id returns event details
- [ ] PUT /api/events/:id updates an event (owner only)
- [ ] DELETE /api/events/:id removes an event (owner only)
- [ ] Event fields: title, description, location, date/time, category
- [ ] Input validation with appropriate error responses
