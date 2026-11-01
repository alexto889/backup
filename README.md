# Handover

Team task board that hands tasks to the Secondary Owner when someone logs leave, runs a capacity check, and flags at-risk work for the Team Lead.

A static site: one `index.html`, no build step.

## Deploy on Vercel
1. Import this GitHub repo at vercel.com/new.
2. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
3. Deploy.

## Notes
- Demo data and settings are stored in the browser (localStorage). Nothing is shared between users yet.
- Slack alerts are shown as an outbox of ready-made payloads. Posting to a Slack webhook needs a small server relay, because browsers cannot call Slack webhooks directly.
- Fonts (Poppins, JetBrains Mono) load from Google Fonts.
