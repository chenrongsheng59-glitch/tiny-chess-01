# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/chenrongsheng59-glitch/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/chenrongsheng59-glitch/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

An original chess engine in under 4 KB of Python: iterative-deepening negamax with alpha-beta pruning, a transposition table, quiescence search (captures, promotions and check evasions), MVV-LVA and killer move ordering, and a piece-square evaluation with a middlegame/endgame king blend. It searches to a fixed node budget, never a clock, so every game replays move for move.

## Run it

```sh
MAKEFUN_ENV_URL=<env url> python3 main.py
```

It plays a full gauntlet trial through the env at that URL, one game after another, and exits when every game is over.

---

<sub>Entered on [make.fun](https://make.fun/?ref=gqgrrky0&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
