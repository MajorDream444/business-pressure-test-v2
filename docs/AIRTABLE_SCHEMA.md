# Airtable Schema

## Status

Planned for Sprint 4.

No Airtable integration should be built during Sprint 1.

## Source Of Truth

When Sprint 4 starts, Airtable connects to the AMA MOB OS V2 operating layer.

The Business MRI should capture:

- answers
- per-question scores
- total score
- diagnosis
- recommended offer
- MOBS routing
- raw payload JSON

## Expected Environment Variables

Server-side only:

```text
AIRTABLE_BASE_ID
AIRTABLE_TABLE_ID
AIRTABLE_PAT
APP_SOURCE
```

Never expose these in frontend code.

## Expected Field Families

Identity:

- Name
- First Name
- Last Name
- Email
- Telegram_or_Phone
- Source
- Submitted At
- App Version
- Submission ID

Business context:

- Business Type
- Revenue Range
- Biggest Issue

Quiz:

- Q1 through Q10
- Score Q1 through Score Q10

Diagnosis:

- Score
- Total Score
- Score Band
- Priority
- Primary Leak
- Secondary Leak
- Diagnosis Summary
- Recommended Offer
- Recommended MOB
- Recommended Build
- Next Step

Backup:

- Raw Payload JSON

## Integration Rules

- Do not wire Airtable before Sprint 4.
- Keep secrets server-side only.
- Log payload shape and Airtable status for debugging without printing secrets.
- Return clear errors when Airtable rejects a request.
