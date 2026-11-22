# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/somempark/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/somempark/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,096 bytes of Python. 0x88 board, alpha-beta search with principal variation search, quiescence search, a transposition table, killer and history move ordering, and piece-square evaluation. It plays the house gauntlet through the make.fun env, one game after another, searching to a fixed node budget per move so every trial replays deterministically.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=cheq5jyz&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
