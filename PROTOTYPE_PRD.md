# PRD: Peopleshift Venue Request Portal — Portfolio Prototype

## Product Overview
A standalone HTML prototype showcasing the Peopleshift Venue Request Portal — an internal tool that streamlines how Account Executives (AEs) submit venue, hotel, and transport requests for corporate training programs, and how Project Officers (POs/PMs) manage them.

## Target User (Portfolio Audience)
- Hiring managers / recruiters reviewing Luqman's LinkedIn portfolio
- Tech leads evaluating product/ops tooling capability
- Peopleshift stakeholders seeing a demo of the system

## Core Screens (MVP)

### 1. Dashboard (PM View)
- KPI cards: Total Requests, Pending, In Progress, Completed
- Request table with status badges, client names, dates
- Quick filters by status

### 2. New Request Form (AE View)
- Multi-step wizard: Client Info → Kebutuhan (Venue/Hotel/Transport) → Detail → Review & Submit
- Bus calculator embedded in transport step
- Clean form validation UX

### 3. Request Detail (PM View)
- Full request data with status timeline
- Auto-match suggestion panel (venue/hotel recommendations from DB)
- Comment thread
- Action buttons: Approve, Assign, Complete

### 4. Bus Calculator (Utility)
- Input: jumlah peserta, wilayah, tipe kendaraan
- Output: recommended fleet + cost estimate
- Rate management table

### 5. Analytics (PM View)
- Monthly request volume chart
- Status distribution donut
- Top clients & regions

## Tech Constraints
- **Single HTML file** — no server, no API, no external dependencies except CDN
- All data is mock/sample — no real client data
- Must open in any browser offline
- Peopleshift branding: Navy (#1A1F3A) + Orange (#E8571E) + White

## Success Criteria
- Looks production-ready in screenshots
- Demonstrates full workflow: submit → track → manage → analyze
- Downloadable and works offline
