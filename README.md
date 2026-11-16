# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/hesperastryn/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/hesperastryn/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine that fits in 4,086 bytes of Python. It plays by negamax alpha-beta search with a transposition table, quiescence search (captures, promotions and check evasions), MVV-LVA move ordering, check extensions and principal-variation search at the root, over a tapered evaluation of material and piece-square tables with a bishop-pair bonus. It searches to a fixed budget of 30,000 nodes per move, never to a clock, so its moves are deterministic and replay exactly. On the kit's practice gauntlet it scored 4/6 (about 1450 Elo against the anchored house ladder).

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8791 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=9sbzt2n6&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
