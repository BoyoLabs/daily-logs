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

- [2026-09-04](2026/09/2026-09-04.md) — the chat frontend reskinned to amber phosphor with replies rendered as terminal output rather than chat, a resume-a-past-session picker that needed a second pass before it stopped opening blank, and a self-inflicted false alarm about a tunnel watchdog traced to a wrong-account schedule check
- [2026-09-03](2026/09/2026-09-03.md) — the mobile chat frontend restyled as a real terminal session, and per-file share links added to the file server, then broken twice by the same change and fixed both times
- [2026-09-01](2026/09/2026-09-01.md) — a procedural goblin figurine built in Blender via metaballs, plus a full chess puzzle-racer service built, hardened, and torn down the same day once it turned out to duplicate an existing service at real scale
- [2026-08-29](2026/08/2026-08-29.md) — two mobile chat frontend bugs fixed (a hardcoded 1MB message cap, and a stale connection after backgrounding), plus a third bug where full-auto mode was silently auto-answering multiple-choice questions instead of waiting for a tap
- [2026-08-28](2026/08/2026-08-28.md) — the castle walkaround turned into a real timed game: random goblin spawns, a 3-minute clock, live scoring, and a replay screen
- [2026-08-27](2026/08/2026-08-27.md) — a first-person browser walkaround built from a 3D-printed castle STL, a camera-FOV bug and a caching false-alarm both chased down, mobile touch controls added, and a second STL turned into a hittable goblin enemy colored by a from-scratch mesh-thickness heuristic
- [2026-08-25](2026/08/2026-08-25.md) — a phone-friendly chat frontend for Claude Code shipped with approve/deny cards and a local-model fallback, the internal troubleshooting-script host retired, and a first real test drive turned up three rough edges to chase
- [2026-08-24](2026/08/2026-08-24.md) — scoping kicked off for a new multi-session project: a custom AI-CLI-first Arch-based Linux distro with an MVP plan agreed but not yet started
- [2026-08-21 – 2026-08-22](2026/08/2026-08-21_2026-08-22.md) — a braille-ASCII webcam render experiment, two dead nav tabs dropped from the income dashboard (and its terminal client), and a three-round battlestation theme pass: de-glowed, re-colored to a muted amber, then polished toward a cleaner SaaS look
- [2026-08-20](2026/08/2026-08-20.md) — file server gains markdown and spreadsheet file types plus a real edit-anywhere upgrade, a broken inline script caught and fixed along the way, keyboard nav added to the new grid editor, two CSS overflow bugs squashed

## Scope

Only substantive Boyo Labs activity — real work, decisions, experiments, fixes —
sourced from what actually happened that day. Sensitive information (credentials,
account numbers, real name, network identifiers, private URLs/hostnames) is scrubbed
before anything is pushed.
