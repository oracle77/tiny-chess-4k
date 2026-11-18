# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/oracle77/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/oracle77/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A tiny chess engine in 4 KB of Python, built for make.fun's "Build the strongest chess engine in 4 KB of Python" bounty. 0x88 board, negamax with alpha-beta, quiescence search, transposition table, killer moves and MVV-LVA ordering, material + piece-square evaluation. It searches to a fixed node budget, never a clock, so replays play the same moves.

## Run it

```sh
python3 main.py
```

It plays the gauntlet through the env at `MAKEFUN_ENV_URL`: `POST /game` serves the game in play, `POST /move` plays a move in UCI.

---

<sub>Entered on [make.fun](https://make.fun/?ref=5n6bz897&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
