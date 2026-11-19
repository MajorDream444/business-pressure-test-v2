[![Edit on Hanzo](https://hanzo.ai/badges/edit-on-hanzo.svg)](https://hanzo.app/dev?repo=https%3A%2F%2Fgithub.com%2FMajorDream444%2Fbusiness-pressure-test-v2)

# Business Pressure Test V2

Business Pressure Test V2 is the front door for Client Clarity OS and the future Business MRI layer.

The repo starts as a local-first diagnostic experience. Its job is to turn a static business quiz into an animated, recommendation-producing Business MRI without drifting into backend systems too early.

## Mission

Diagnose business pressure before selling.

The first usable product should help a founder answer:

- Where is the business leaking?
- What pressure pattern is showing up?
- What should be built first?
- Which internal MOB should own the next move?

## Current Scope

This first foundation pass is doctrine and structure only.

Sprint 1 should build:

- Landing page
- Quiz
- Score
- Diagnosis
- Result screen

Sprint 1 should not build:

- Airtable integration
- Authentication
- Payments
- CRM
- Automation
- Dashboards

Backend integrations wait until Sprint 4.

## Repo Map

```text
docs/       Product doctrine, scope, schemas, routing, animation plan, master prompt
research/   Source-grounded context for future Graphify and agent navigation
src/        React app source, organized for the future MRI experience
public/     Static assets
```

## Sprint Roadmap

### Sprint 1: Business MRI Prototype

Build the local experience only:

- Landing page
- Quiz
- Score
- Diagnosis
- Result screen

No Airtable. No authentication. No payment. No CRM. No automation.

### Sprint 2: Animated MRI

Install `animejs` and add:

- Question transitions
- Progress meter
- Score reveal
- Leak map animation
- CTA pulse

Motion must serve clarity.

### Sprint 3: Business Intelligence Layer

Add intelligence outputs:

- Primary leak
- Secondary leak
- MOBS routing
- Blueprint recommendation

Example:

```text
Primary Leak: Lead Flow
Secondary Leak: Follow-Up
Recommended MOB: Provocateurs
Recommended Build: Client Acquisition Engine
```

### Sprint 4: Airtable Integration

Connect AMA MOB OS V2 and capture:

- Answers
- Scores
- Diagnosis
- Recommended offer
- MOBS routing

Airtable is the source of truth, but it is not wired until Sprint 4.

## Operating Rules

- Diagnose before selling.
- Motion serves clarity.
- Every answer produces intelligence.
- Every score produces a recommendation.
- Keep Sprint 1 local and lightweight.
- Do not overengineer.
- Do not add auth, subscriptions, dashboards, CRM, payments, or automation before the roadmap calls for them.

## Development

```bash
npm install
npm run lint
npm run build
npm run dev
```
