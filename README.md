# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/tony0976/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/tony0976/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A compact 4KB Python chess engine: 0x88 board, negamax with alpha-beta pruning, iterative deepening under a fixed node budget (never a clock, so replays are deterministic), quiescence search on captures and promotions, transposition table with incremental Zobrist hashing, killer-move and MVV-LVA ordering, and material + piece-square evaluation. Local practice Elo ~1191.

## Run it

```sh
MAKEFUN_ENV_URL=$MAKEFUN_ENV_URL python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=0gzpxxg0&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
