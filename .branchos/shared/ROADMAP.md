# Roadmap: EventSphere MVP

> If discovering events and buying tickets becomes easy, more people will attend events and organizers will adopt a centralized platform.

**Milestones:** 5 | **Features:** 16

---

## M1: Foundation (0/3 features complete)

Core project scaffolding, database schema, and authentication.

| # | Feature | Status | Depends On |
|---|---------|--------|------------|
| F-001 | Project scaffolding & dev environment | unassigned | -- |
| F-002 | Database schema & ORM setup | unassigned | F-001 |
| F-003 | User authentication & accounts | unassigned | F-002 |

---

## M2: Event Management (0/3 features complete)

Organizers can create and manage events with ticket types.

| # | Feature | Status | Depends On |
|---|---------|--------|------------|
| F-004 | Event CRUD API | unassigned | F-002 |
| F-005 | Organizer event creation form | unassigned | F-003, F-004 |
| F-006 | Event details page | unassigned | F-004 |

---

## M3: Discovery (0/3 features complete)

Users can browse and filter events.

| # | Feature | Status | Depends On |
|---|---------|--------|------------|
| F-007 | Event listing API with filters | unassigned | F-004 |
| F-008 | Event browse page with cards | unassigned | F-007 |
| F-009 | Category, date & location filters | unassigned | F-008 |

---

## M4: Ticketing (0/4 features complete)

Ticket purchase flow with Stripe integration and digital ticket delivery.

| # | Feature | Status | Depends On |
|---|---------|--------|------------|
| F-010 | Ticket type & inventory model | unassigned | F-004 |
| F-011 | Stripe checkout integration | unassigned | F-003, F-010 |
| F-012 | Purchase confirmation & ticket generation | unassigned | F-011 |
| F-013 | Digital ticket display with unique ID | unassigned | F-012 |

---

## M5: Dashboards (0/3 features complete)

User and organizer dashboards for tracking events and sales.

| # | Feature | Status | Depends On |
|---|---------|--------|------------|
| F-014 | User "My Events" dashboard | unassigned | F-012 |
| F-015 | Organizer dashboard with sales tracking | unassigned | F-005, F-012 |
| F-016 | Event status management (draft/published/closed) | unassigned | F-005 |
