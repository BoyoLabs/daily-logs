# Boyo Labs: Daily Logs

*Part of [Boyo Labs](https://www.boyolabstech.com).*

A day-by-day running record of Boyo Labs activity — whatever happened that day across
software, hardware, infra, and research, in whatever mix actually occurred. Lighter
weight than [`project-logs`](https://github.com/BoyoLabs/project-logs), which holds
deep single-topic write-ups on request; this repo is the always-on, lower-ceremony
companion — a day's worth of notes reviewed once and pushed, not a polished
investigation.

## Structure

Entries are organized by date, newest folders added as time goes on:

```
YYYY/
  MM/
    YYYY-MM-DD.md
```

For example, an entry from August 14th, 2026 lives at `2026/08/2026-08-14.md`.

## Recent Entries

The 10 most recently pushed days, newest first:

- [2026-08-20](2026/08/2026-08-20.md) — file server gains markdown and spreadsheet file types plus a real edit-anywhere upgrade, a broken inline script caught and fixed along the way, keyboard nav added to the new grid editor, two CSS overflow bugs squashed
- [2026-08-19](2026/08/2026-08-19.md) — remote-control's flaky restarts fixed with a real reachability check; homepage now links to recent/random daily+research logs with tiny AI summaries; a new troubleshooting-script sharing tool and a second-machine bootstrap prompt both shipped; a high-risk mixed-RAM test failed to POST
- [2026-08-18](2026/08/2026-08-18.md) — a new clip/photo mashup video tool built and iterated through the day, a full-length landscape mode with its own voiceover editor, GPU-offloaded encoding, an in-app camera recorder
- [2026-08-17](2026/08/2026-08-17.md) — statement of intent published, a kernel update's dropped security module traced and fixed, remote-desktop relay root-caused and given a self-heal check, dashboard restart controls simplified, a task calendar added to the dashboard
- [2026-08-16](2026/08/2026-08-16.md) — print server storefront shipped with a pause-orders switch and multi-part combined print jobs
- [2026-08-15](2026/08/2026-08-15.md) — dashboard tab split and ops tools, ssh terminal auto-lock restored, mobile STL upload fix
- [2026-08-14](2026/08/2026-08-14.md) — logs repo split in two, business card design finished, automatic system updates shipped

## Scope

Only substantive Boyo Labs activity — real work, decisions, experiments, fixes —
sourced from what actually happened that day. Sensitive information (credentials,
account numbers, real name, network identifiers, private URLs/hostnames) is scrubbed
before anything is pushed.
