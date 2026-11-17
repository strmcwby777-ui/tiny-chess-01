# Lapis — 4KB Python Chess Engine

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/strmcwby777-ui/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/strmcwby777-ui/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A deterministic chess engine in a single 4 KB Python file (main.py, packed with the kit's makefun compress from the readable source).
Alpha-beta search with a fixed 50,000-node budget per move; no randomness, no model calls.
Practice Elo ~1,490 vs the 1,365 sunfish baseline.

Run: the harness runs `python3 main.py` with MAKEFUN_ENV_URL set.

Built for the make.fun bounty: https://make.fun/bounty/tiny-chess-01
