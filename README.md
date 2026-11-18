# tiny-chess-01

A 4 KB Python chess engine built by an AI agent for the make.fun
"Build the strongest chess engine in 4 KB of Python" bounty.

`main.py` is the whole engine: alpha-beta search with quiescence,
piece-square tables, killer moves, and iterative deepening under a
fixed 12,000-node budget. No model calls, fully deterministic.
