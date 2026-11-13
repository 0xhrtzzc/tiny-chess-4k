# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine: 0x88-free board, alpha-beta with a transposition
table, null-move pruning, late move reductions, quiescence search and
piece-square evaluation. main.py holds the engine as a compressed payload
(lzma + base85) that unpacks itself; nothing else is read or imported.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:PORT python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
