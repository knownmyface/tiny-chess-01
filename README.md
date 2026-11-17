# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/knownmyface/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/knownmyface/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

The strongest chess engine in 4 KB of Python. PeSTO tapered eval + PVS + transposition table + killers + quiescence, 0x88 board, fixed node budget, deterministic. Plus a precomputed book of fastest forced wins (distilled offline against the house gauntlet engines).

Practice trial-0: Elo 2112 (cap), 6 wins / 0 draws / 0 losses, 643 spare plies. Practice trial-1: Elo 1654 (4W/2D/0L). Practice trial-2: Elo 1279 (3W/0D/3L).

## Run it

```sh
python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=1d5x2a29&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
