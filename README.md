# osint-ctf-labs

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Donate](https://img.shields.io/badge/Donate-crypto-ea4aaa?logo=githubsponsors&logoColor=white)](https://github.com/renkagod/.github/blob/main/DONATE.md)

Open-source intelligence **CTF challenge pack** — multi-phase puzzles built around public records, Wikipedia, aviation databases, and transcript research. No Docker required; designed for events, classrooms, and self-study.

Originally authored for Caplag CTF.

## Features

| Lab | Theme | Skills |
|-----|--------|--------|
| [01 — Lost Altar](labs/01-lost-altar/) | WWII church altarpiece, displacement & restoration | Geo/historical OSINT, Wikipedia (native language), heritage registries |
| [02 — Flight 4836](labs/02-flight-4836/) | 2024 Baku–Grozny accident | Aviation databases, CVR transcripts, procedure naming |

Each lab has **3 phases** with independent flags. Player briefs live in `public/description.md`; full walkthroughs in `WRITEUP.md` (spoilers).

## Quick start

1. Pick a lab and read `public/description.md` (give this to players).
2. Host flags in your CTF platform (`meta.yml` lists expected values for checkers).
3. After the event, share `WRITEUP.md` for debrief.

## Flag format

Demo flags use `FLAG{...}`. Replace before running a public competition.

## Repository layout

```
osint-ctf-labs/
├── README.md
├── LICENSE
└── labs/
    ├── 01-lost-altar/
    └── 02-flight-4836/
```

## Ethics

- Use only public sources and fair-play rules (no harassment, no illegal access).
- Lab 02 references real accident material — treat transcripts and victims with respect in debriefs.

## Support

If this project is useful to you, you can support it with crypto: [donation addresses](https://github.com/renkagod/.github/blob/main/DONATE.md).

## License

[MIT](LICENSE) — Copyright (c) 2026 [renkagod](https://github.com/renkagod).

---

## Русский

Два OSINT-квеста по три этапа: историко-культурный (утраченный алтарь) и авиационный (рейс, CVR, процедуры). Без контейнеров — только описание, writeup и эталонные флаги для платформы.
