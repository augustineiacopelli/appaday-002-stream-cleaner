# AppADay #002 — Stream Cleaner

**Category:** G — Games and Interactive
**Date:** 2026-05-08
**Build time:** ~2 hours

## What it does

Drag the hose across the urinal screen and hold to blast it clean before time runs out. Stream power ramps up at the start and fades at the end — just like real life. Clear 80% to advance through 5 levels. Features a leaderboard, level flash animations, and a score system that rewards speed.

## How to play

- Press and drag anywhere on the pad to move the hose
- Hold while dragging to stream — the pad cleans wherever the hose is positioned
- Sweep the full surface to hit the 80% threshold and advance
- Stream power builds during the first 5% of each level's time and fades during the last 5%
- Scores are saved locally — top 20 entries tracked on the leaderboard

## Levels

| Level | Time | Goal |
|-------|------|------|
| 1 | 25 sec | 80% |
| 2 | 20 sec | 82% |
| 3 | 16 sec | 84% |
| 4 | 13 sec | 86% |
| 5 | 10 sec | 88% |

## Tech

Single-file HTML/CSS/JavaScript. Canvas-based rendering with per-pixel ImageData cleaning. No dependencies, no build step.

## Notes

Stream mechanics are intentionally simplified for the daily time budget. The aiming system and stream physics are good candidates for a future upgrade day.

---

[← Back to AppADay Portfolio](../index.html)
