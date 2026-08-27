# tl-webinar-cycle

Machine-readable webinar cycle dates for the TL ClickFunnels landers (public info only — the same dates shown on the pages).

- `tl-cycle.json` — `next` = upcoming webinar (opt-in/thank-you pages), `last` = most recent webinar that ran (booking/replay deadline pages, deadline = last + 4 days 12:00 AM ET).
- Consumed by the pages' Header tracking-code blocks via raw.githubusercontent.com.
- Written by the TL n8n box (scheduled sync from the cycle table). Manual edits get overwritten.
