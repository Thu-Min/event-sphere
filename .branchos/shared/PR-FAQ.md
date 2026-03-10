# PR-FAQ: EventSphere MVP (Events & Ticket Platform)

**Author:** Product Team  
**Date:** 2026-03-10  
**Status:** Draft  
**Product:** EventSphere (MVP)

---

# Press Release

**FOR IMMEDIATE RELEASE**

### EventSphere Launches a Simple Way to Discover Events and Buy Tickets Online

Bangkok — Today, EventSphere announced the launch of its new event discovery and ticketing platform designed to make finding and attending events easier than ever.

EventSphere allows users to browse local events, view event details, and purchase tickets through a streamlined digital experience. Event organizers can publish events in minutes and manage ticket sales through a simple dashboard.

With EventSphere, customers can:

- Discover local events by category, date, or location
- Purchase digital tickets instantly
- Receive confirmation and access tickets online
- Track upcoming events in their personal dashboard

For organizers, EventSphere offers:

- Fast event creation
- Ticket inventory management
- Real-time ticket sales tracking
- Digital ticket delivery

“People want to attend more events, but discovering and buying tickets is often fragmented and inconvenient,” said the EventSphere product team. “Our goal is to make attending events effortless while giving organizers a simple platform to reach audiences.”

The MVP launch focuses on essential event discovery and ticket purchasing capabilities, with additional features such as organizer analytics, promotions, and mobile apps planned for future releases.

EventSphere is available starting today via web browser.

---

# Customer Problem

Event discovery and ticket purchasing are often frustrating due to:

1. **Fragmented discovery**
   - Events are spread across social media, websites, and messaging apps.

2. **Complicated ticket purchasing**
   - Many systems require multiple steps or manual confirmation.

3. **Lack of centralized event tracking**
   - Users cannot easily track the events they plan to attend.

4. **Difficult event publishing for organizers**
   - Creating events and managing ticket sales can require technical knowledge or multiple tools.

Customers want a **simple, centralized platform** for discovering events and buying tickets.

---

# Solution Overview

EventSphere MVP provides a minimal but functional event platform that allows users to:

- Discover events
- View event details
- Purchase tickets
- Manage purchased tickets

Organizers can:

- Create events
- Configure ticket types
- Track ticket sales

The MVP focuses on the **core ticketing workflow**, avoiding unnecessary complexity while validating product-market fit.

---

# Key MVP Features

## 1. Event Discovery

Users can browse events with filters:

- Date
- Category
- Location

Event cards display:

- Event name
- Date
- Venue
- Ticket price
- Availability

---

## 2. Event Details Page

Each event page includes:

- Event description
- Venue location
- Event schedule
- Ticket types
- Remaining ticket count

---

## 3. Ticket Purchase

Customers can:

- Select ticket type
- Choose quantity
- Complete checkout

After purchase:

- Confirmation page appears
- Ticket stored in user account

---

## 4. Digital Tickets

Tickets are available in the user dashboard with:

- Ticket ID
- Event info
- QR code (future enhancement)

---

## 5. Organizer Event Creation

Organizers can create events by entering:

- Event title
- Description
- Location
- Date/time
- Ticket types
- Ticket quantity
- Ticket price

---

## 6. Organizer Dashboard

Organizers can view:

- Event status
- Tickets sold
- Remaining tickets

---

# Customer FAQ

### Q: What is EventSphere?

EventSphere is a platform that helps users discover events and purchase tickets online.

---

### Q: Do I need an account to buy tickets?

Yes. An account ensures your tickets are stored and accessible anytime.

---

### Q: How do I access my tickets after purchasing?

Tickets are available in your **My Events** dashboard immediately after purchase.

---

### Q: Can I transfer tickets?

Ticket transfer is **not included in the MVP** but may be added in future versions.

---

### Q: What types of events are supported?

The platform supports events such as:

- Concerts
- Workshops
- Conferences
- Meetups
- Community events

---

# Internal FAQ

### Q: Why build this MVP?

The goal is to validate:

- Demand for a simplified event platform
- Ticket purchase conversion rates
- Organizer willingness to publish events

---

### Q: What is explicitly out of scope for MVP?

The MVP excludes:

- Mobile apps
- Payment splitting for organizers
- Promotions or discount codes
- Seat selection
- Ticket resale
- QR check-in systems

---

### Q: What are the success metrics?

Primary metrics:

- Event creation rate
- Ticket purchase conversion rate
- Repeat users
- Tickets sold per event

Secondary metrics:

- Time to create event
- Checkout completion rate

---

### Q: What technical architecture will support the MVP?

Proposed stack:

Frontend

- React / Next.js

Backend

- Node.js / Express or NestJS

Database

- SQL Lite

Payments

- Stripe

Hosting

- AWS / Vercel

---

### Q: How will fraud or ticket duplication be handled?

For MVP:

- Unique ticket IDs
- Account-based ticket access

Future versions may include:

- QR validation
- Check-in scanning
- Anti-resale protections

---

# Future Roadmap

Potential enhancements include:

- QR ticket scanning
- Mobile app
- Event recommendations
- Organizer analytics
- Promo codes
- Seat selection
- Ticket transfer
- Waitlists
- Notifications

---

# Summary

EventSphere MVP focuses on validating a simple hypothesis:

> If discovering events and buying tickets becomes easy, more people will attend events and organizers will adopt a centralized platform.

The MVP provides only the essential functionality needed to test this hypothesis while minimizing development complexity.
