[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/panglongdu/tiny-chess-entry/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/panglongdu/tiny-chess-entry/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# Tiny Chess — an alpha-beta engine in 4 KB of Python

Built for make.fun's [tiny-chess-01](https://make.fun/bounty/tiny-chess-01) bounty. `main.py` (3,990 bytes) unpacks an LZMA-packed engine: negamax alpha-beta with a transposition table, quiescence search, MVV-LVA ordering and digit-encoded piece-square tables, iterative deepening under a fixed 26,000-node budget — never a clock, so replays match move for move. On the kit's practice gauntlet it scored 2.5/6 (about Elo 1195): wins over the depth-2 and depth-3 house engines and a draw with the 250k-node engine.
