# SeaPass: Batangas Port Smart Automated Navigation and Passenger System

> A System Integration Bidding Simulation project proposing a modernized, digital-first ecosystem for Batangas Port.

## 📋 Overview

**SeaPass** reimagines Batangas Port as a fast, passenger-first terminal — the kind of experience you'd expect from an international airport. It replaces manual, fragmented ticketing with a unified digital platform that lets commuters book, pay, and stay informed in real time.

**Team (Group 3):**
- Emanuel Cruzat
- Lance Pria
- Mikayla Banaag
- Kathleen Bool
- Francis Panganiban

## 🎯 Problem Statement

Batangas Port currently suffers from:

1. **Limited booking & payment options** — manual, cash-based transactions and fragmented ticketing booths force commuters to queue in person.
2. **Long ticket queues** — physical bottlenecks at gates cause boarding delays, overcrowding, and frustration.
3. **Lack of real-time information** — commuters have little to no visibility into schedule shifts, weather disruptions, or delays until they're already at the terminal.

An existing system, **Oras Pass**, only handles scheduling — it has no active payment integration and its QR codes expire 3 hours before departure, creating a major bottleneck.

## 🚀 Core Objectives

1. **Digitize Payments** — enable advance ticket reservation and payment in a single online transaction.
2. **Optimize Flow** — drastically speed up boarding and eliminate chaotic queues at terminal gates.
3. **Empower Commuters** — give on-demand access to real-time schedules, gate updates, and travel alerts via mobile.

## 🧩 System Architecture (5 Subsystems)

| Subsystem | Function |
|---|---|
| **Unified Commuter Booking App** | Web/mobile app connecting to multiple ferry & RORO operator databases for real-time booking |
| **Self-Service Cashless Payment Kiosks** | On-site kiosks for walk-in passengers (QR/RFID, e-wallets, cards) — with local edge caching as an offline fallback |
| **Predictive Demand & Congestion Forecasting** | Analyzes foot traffic and historical data to forecast peak hours |
| **Weather-Based Trip Disruption Prediction** | Integrates PAGASA/Coast Guard alerts to auto-notify passengers of cancellations |
| **24/7 Virtual Assistant / Chatbot** | Handles commuter queries and disruption notifications |

## 💰 Cost Evaluation

**Total Estimated Project Cost: ₱493,640**

### Labor Costs — ₱298,640 (760 hours across 16 weeks)

| Phase | Weeks | Hours | Cost |
|---|---|---|---|
| 1. Project Planning & Feasibility | 1–3 | 120 | ₱47,440 |
| 2. System Analysis & Architecture Design | 4–7 | 136 | ₱57,200 |
| 3. Development & Integration | 8–11 | 288 | ₱88,000 |
| 4. Testing & Quality Assurance | 12–14 | 152 | ₱29,800 |
| 5. Deployment, Training & Handover | 15–16 | 112 | ₱32,800 |

### Non-Labor Resources — ₱158,000

- **Hardware & Equipment:** 3 self-service kiosks (₱135,000), port network equipment (₱4,000), backup UPS units (₱4,000)
- **Cloud & Services:** Server hosting, database storage, AI prediction APIs, payment gateway, backup storage, domain registration (₱15,000)

## 📅 Project Timeline (16 Weeks, Sept–Dec 2026)

| Phase | Weeks | Focus |
|---|---|---|
| **Phase 1** | 1–3 | Stakeholder alignment, requirement gathering, site surveys |
| **Phase 2** | 4–7 | API design, cloud infrastructure layout, hardware procurement, data mapping |
| **Phase 3** | 8–11 | Web/mobile app development, kiosk software, AI model training, turnstile integration |
| **Phase 4** | 12–14 | Load testing, penetration testing, end-to-end boarding gate simulations |
| **Phase 5** | 15–16 | On-site installation, staff training, public go-live, performance monitoring |

## ⚠️ Risk Management

| Risk | Mitigation |
|---|---|
| **System Downtime** | Redundant cloud backups, on-site UPS units, local edge servers with offline queue sync |
| **Cybersecurity Risk** | End-to-end encryption, regular penetration testing, compliance with RA 10173 (Data Privacy Act of 2012) |
| **Inaccurate AI Predictions** | 2-week model training/fine-tuning phase before rollout, regular maintenance, review by port management |

## 📢 Communication Plan

- **Channels:** MS Teams (meetings), SMS & Viber (immediate updates), Email (wide dissemination)
- **Meetings:** Weekly full-team sync via MS Teams; bi-weekly hybrid sub-team updates
- **Escalation:**
  1. New issues → internal alert within 24 hours
  2. Persisting bottlenecks → Project Manager reallocates resources
  3. Critical blockers → emergency meeting with Batangas Port stakeholders

## ❓ Anticipated Q&A Highlights

- **Why is this better than the manual process?** Splits ticketing into two channels (online pre-booking + on-site kiosks), cutting queue time and removing manual hassle.
- **Why does this beat Oras Pass?** Oras Pass is scheduling-only, with no active payments and a 3-hour QR expiration window that creates bottlenecks. SeaPass adds integrated payments and eliminates that expiration risk.
- **What if there's no internet connection?** Kiosks and turnstiles fall back to local edge caching, validating QR codes stored locally.
- **What about non-tech-savvy commuters?** Self-service kiosks (McDonald's-style UI) handle walk-ins without requiring a smartphone.
- **Is the budget justified?** At hundreds to thousands of passengers per day (especially during peak holiday rushes), a ₱493,640 full system overhaul is a strong operational return on investment.

---
*System Integration Bidding Simulation — BatStateU*
