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

- [2026-09-13](2026/09/2026-09-13.md) — a single-app OSRS streaming host scoped out, then the target quietly shifted to a locked-down browser tab, tracing a corporate-network media-path mismatch as the real cause of an existing tool's flakiness
- [2026-09-12](2026/09/2026-09-12.md) — a standalone terminal status tool scrapped mid-build and rebuilt as an AI-native app instead, catching a home-directory-shortcut bug along the way, plus a daily-log gap traced to a genuinely quiet stretch rather than a broken process
- [2026-09-10](2026/09/2026-09-10.md) — a compressed Intent/Shape/Proof prompt model developed and trialed on a Steam Deck controller tester that failed its on-device test and got published as an intentional one-shot rather than debugged, plus a coworker's prompt-practice-site idea scoped out and deliberately shelved
- [2026-09-08](2026/09/2026-09-08.md) — the daily-log capture rules rewritten so landed conversation counts, a stale-DNS cleanup decision left opportunistic, and a filament-runout bug root-caused and fixed with auto-pause, a shared park routine, and a decoupled, trustworthy alert
- [2026-09-06](2026/09/2026-09-06.md) — the browser remote-desktop stream torn down top to bottom after turning out to be perfectly healthy and simply unused, with a blast-radius sweep first and one DNS record left as a known loose end
- [2026-09-04](2026/09/2026-09-04.md) — the chat frontend reskinned to amber phosphor with replies rendered as terminal output rather than chat, a resume-a-past-session picker that needed a second pass before it stopped opening blank, and a self-inflicted false alarm about a tunnel watchdog traced to a wrong-account schedule check
- [2026-09-03](2026/09/2026-09-03.md) — the mobile chat frontend restyled as a real terminal session, and per-file share links added to the file server, then broken twice by the same change and fixed both times
- [2026-09-01](2026/09/2026-09-01.md) — a procedural goblin figurine built in Blender via metaballs, plus a full chess puzzle-racer service built, hardened, and torn down the same day once it turned out to duplicate an existing service at real scale
- [2026-08-29](2026/08/2026-08-29.md) — two mobile chat frontend bugs fixed (a hardcoded 1MB message cap, and a stale connection after backgrounding), plus a third bug where full-auto mode was silently auto-answering multiple-choice questions instead of waiting for a tap
- [2026-08-28](2026/08/2026-08-28.md) — the castle walkaround turned into a real timed game: random goblin spawns, a 3-minute clock, live scoring, and a replay screen

## Scope

Only substantive Boyo Labs activity — real work, decisions, experiments, fixes —
sourced from what actually happened that day. Sensitive information (credentials,
account numbers, real name, network identifiers, private URLs/hostnames) is scrubbed
before anything is pushed.
