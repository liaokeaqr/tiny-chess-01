# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/liaokeaqr/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/liaokeaqr/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4,096-byte Python chess engine for make.fun tiny-chess-01. 75k-node 0x88 search with a fixed node budget, deterministic, stdlib only. Practice Elo mean 1315 (trials 1654 / 1191 / 1099).

## Run it

```sh
MAKEFUN_ENV_URL=<env-url> python3 main.py
```

The engine talks to the make.fun environment over HTTP (`/game`, `/move`, `/resign`), 10s per move, no clock, no file reads, no randomness except fixed-seed Zobrist keys.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
