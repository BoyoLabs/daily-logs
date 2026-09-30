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

- [2026-09-29](2026/09/2026-09-29.md) — Ironman's second area Oakhollow shipped with two new skills and a second boss, a playtest-only rendering bug caught what green tests missed, plus a tape dispenser reprint and Steam Deck button macros
- [2026-09-28](2026/09/2026-09-28.md) — Ironman, an offline OSRS-style RPG, built from design calls to v0.4.0 in a day: file-server playable, Deck-tested, a combat triangle and a merged Melee skill, plus a site outage traced to a file-ownership slip
- [2026-09-26](2026/09/2026-09-26.md) — slow internet and stuck print uploads narrowed step by step to the uploading device, with the server, app and tunnel all ruled out
- [2026-09-21](2026/09/2026-09-21.md) — a `/desk` command giving the income arm a skip-safe glance/standard/deep session, and the paper-trading tab restored with a per-account balance reset and an income withdrawal that never reads as a loss
- [2026-09-17 – 2026-09-18](2026/09/2026-09-17.md) — the Steam Deck and home server articulated as one system, a long search for "one device to rule them all" resolved into deliberately not wanting that, a Steam button remap bug left alone at an upstream wall, and a VOO intraday move email alert built and tuned live to a 0.25% threshold ladder
- [2026-09-10](2026/09/2026-09-10.md) — a compressed Intent/Shape/Proof prompt model developed and trialed on a Steam Deck controller tester that failed its on-device test and got published as an intentional one-shot rather than debugged, plus a coworker's prompt-practice-site idea scoped out and deliberately shelved
- [2026-09-08](2026/09/2026-09-08.md) — the daily-log capture rules rewritten so landed conversation counts, a stale-DNS cleanup decision left opportunistic, and a filament-runout bug root-caused and fixed with auto-pause, a shared park routine, and a decoupled, trustworthy alert
- [2026-09-06](2026/09/2026-09-06.md) — the browser remote-desktop stream torn down top to bottom after turning out to be perfectly healthy and simply unused, with a blast-radius sweep first and one DNS record left as a known loose end
- [2026-09-04](2026/09/2026-09-04.md) — the chat frontend reskinned to amber phosphor with replies rendered as terminal output rather than chat, a resume-a-past-session picker that needed a second pass before it stopped opening blank, and a self-inflicted false alarm about a tunnel watchdog traced to a wrong-account schedule check
- [2026-09-03](2026/09/2026-09-03.md) — the mobile chat frontend restyled as a real terminal session, and per-file share links added to the file server, then broken twice by the same change and fixed both times

## Scope

Only substantive Boyo Labs activity — real work, decisions, experiments, fixes —
sourced from what actually happened that day. Sensitive information (credentials,
account numbers, real name, network identifiers, private URLs/hostnames) is scrubbed
before anything is pushed.
