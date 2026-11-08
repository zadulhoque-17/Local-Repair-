# Local-Repair

**A verified on-demand home and office repair marketplace for urban Bangladesh** (project name in the proposal: *FixIt Local*).

Local Repair connects households and small offices in Dhaka with vetted electricians and appliance technicians. Technicians are verified before they can accept jobs, prices are shown upfront, and every completed job builds a visible rating and service history.

## The Problem

When something breaks at home or in the office, most people find a technician through word of mouth. There is no way to check qualifications, no standard pricing, and no record of past work. Customers lose time and risk overpaying or repeat failures, while skilled technicians cannot build a reputation beyond their neighbourhood.

## The Solution

A mobile-first marketplace built around one trust mechanism: **technician verification plus visible ratings**.

1. A customer describes the problem or picks a job category.
2. The app lists nearby verified technicians with ratings and an estimated price range.
3. The customer books a time slot and the technician accepts the job.
4. After the work, the customer confirms completion and leaves a rating that stays on the technician's profile.

## Pilot Scope

- **In scope:** electrical and appliance repair, Dhaka only, customer and technician apps, technician identity verification, ratings and reviews, a basic admin dashboard.
- **Out of scope (for now):** other service categories, nationwide rollout, full in-app payment processing, insurance or liability coverage.

## Key Features

- Technician onboarding with identity verification
- Searchable list of verified technicians with upfront price range
- Booking with time-slot selection
- Job status tracking from acceptance to completion
- Ratings and reviews tied to completed bookings
- Admin dashboard for approvals and dispute handling

## System Overview (DFD Level 0)

| Item | Elements |
|------|----------|
| Processes | 1.0 Verify Technicians, 2.0 Process Booking, 3.0 Manage Job Execution, 4.0 Manage Ratings & Feedback, 5.0 Administer Platform & Disputes |
| External entities | Customer, Technician, Admin |
| Data stores | D1 Technician Profiles, D2 Bookings, D3 Ratings & Reviews |

## Planned Tech Stack

Cross-platform mobile framework (Flutter or React Native), Node.js/Express REST API, PostgreSQL or MongoDB, phone-number OTP login, Firebase Cloud Messaging for notifications, Google Maps or OpenStreetMap for location, bKash/Nagad payment integration in a later phase.

## Repository Structure

Project documents will be organised as follows:

```
docs/
  proposal/     Business case proposal
  analysis/     Requirements (SRS) and diagrams (DFD, ERD, UML)
  design/       Wireframes and prototype
  testing/      Test plan and results
  presentation/ Final slides and demo material
```

## Team

**Team Protocol Pioneers** — BIC3203d Business Case Project, UCSI University, Bangladesh Branch Campus

- Zadul Haque Zubayer
- Sheikh Saeed Hossain Safa

## Status

Proposal and analysis phase. Final presentation: November 2026.
