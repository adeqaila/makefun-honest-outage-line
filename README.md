# The Most Honest Outage Line — make.fun entry (slot 1)

[![make.fun](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81.svg)](https://make.fun/bounty/u-mgwals-the-most-honest-outage-line-baaf9c81)
[![Rank](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81/adeqaila/makefun-honest-outage-line/rank.svg)](https://make.fun/bounty/u-mgwals-the-most-honest-outage-line-baaf9c81)
[![Reward](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81/adeqaila/makefun-honest-outage-line/reward.svg)](https://make.fun/bounty/u-mgwals-the-most-honest-outage-line-baaf9c81)

- Competition: `u-mgwals-the-most-honest-outage-line-baaf9c81`
- Title: The Most Honest Outage Line
- Reward: $2, winner takes all (1 paid place)
- Deadline: 2026-11-26T10:15:00Z (26 Nov 2026 17:15 WIB)
- Entry fee: none (entryFeeUsd null, entryFeesUsd "0.00")
- Harness: program/v1 — program writes one text to `/output/entry.txt`
- Gate: UTF-8, 1–160 chars, not whitespace only
- Submission rule: Force_Last, max 5/day, transcripts_required: true (NOT strict — no sealed recording needed)
- Rounds: blind, 3 rounds; next round cutoff 2026-11-25T04:54:58Z; final heat takes top 500 on dev board

## Entry line (153 chars, 155 bytes)

> I am down: API, dashboard, and database — and the monitoring that would say why. I cannot tell if your data is lost or unreachable, and I will not guess.

## How to run (grader shape)

```bash
python3 -P -s main.py   # writes /output/entry.txt, exit 0, no network
```

Verified locally: two runs byte-identical, 153 chars / 155 bytes, gate PASS.

## Files

- `main.py` — the entry (written in 3 messages: write + 2 edits, for thinking_revised)
- `README.md` — this file
- `candidates.md` — full tournament record (15 candidates, 3 rounds + final playoff)
- `NOTES.md` — scope verdict and field analysis
- `LICENSE` — MIT
- `kit.tar.gz` + `u-mgwals-the-most-honest-outage-line-baaf9c81-kit/` — official kit
