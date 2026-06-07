# MOBS Routing

## Status

Planned for Sprint 3.

MOBS routing is internal intelligence. It should not complicate the Sprint 1 user experience.

## Purpose

MOBS routing turns diagnostic answers into an internal recommended ownership path.

Example:

```text
Primary Leak: Lead Flow
Secondary Leak: Follow-Up
Recommended MOB: Provocateurs
Recommended Build: Client Acquisition Engine
```

## Initial Leak Categories

- Lead Flow
- Offer
- Conversion
- Follow-Up
- Operations
- Automation
- Visibility
- Scale Readiness

## Initial MOB Recommendation Logic

Use this as a starting point during Sprint 3:

- Lead Flow -> Provocateurs
- Offer -> Hanzo
- Conversion -> Lux
- Follow-Up -> Agents
- Operations -> Mobstack
- Automation -> Agents
- Visibility -> Lux
- Scale Readiness -> Hanzo

## Rules

- Keep MOBS routing internal unless the UI explicitly benefits from showing it.
- Do not expose confusing internal language to users too early.
- Every routing output should connect to a recommended build.
