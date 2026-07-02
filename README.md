# AppADay #002 — Stream Cleaner

**Category:** G — Games and Interactive
**Date:** 2026-05-08
**Build time:** ~2 hours

## What it does

Blast a colored deodorizing screen clean with a pressure washer before time runs out. Drag to aim — the stream arcs up and away from the fixed nozzle, landing further back as you drag higher. Clear 80% or better to advance through 5 levels. Features a leaderboard, level flash animations, increasing aim sway as the level progresses, and a score system that rewards speed.

## How to play

Press and drag on the canvas to aim the stream. Vertical drag position controls how far the stream reaches — drag toward the top of the screen to land further back on the pad, side to side to sweep left and right. Hold while dragging to clean. The stream's power builds during the first few seconds of each level and fades at the end, limiting reach when pressure is low. Aim sway increases as the level progresses, making precise aim harder when the clock is winding down. Scores are saved locally with the top 20 entries tracked on the leaderboard.

## Levels

| Level | Time | Goal |
|-------|------|------|
| 1 | 25 sec | 80% |
| 2 | 20 sec | 82% |
| 3 | 16 sec | 84% |
| 4 | 13 sec | 86% |
| 5 | 10 sec | 88% |

## Tech

Single-file HTML/CSS/JavaScript. Canvas-based rendering with per-pixel ImageData cleaning and a perspective trapezoid mapping system that converts drag position into depth/lateral aim coordinates on a foreshortened hexagonal pad. No dependencies, no build step.

## Notes

Pad depth and stream physics are intentionally simplified for the daily time budget. A full perspective rework with proper foreshortened arc trajectory is logged for a future upgrade day.

---

[← Back to AppADay Portfolio](https://augustineiacopelli.github.io/appaday/)
