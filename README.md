# Tiny Chess 4KB

[![make.fun](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/gishou0930/tiny-chess-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard)
[![reward](https://make.fun/badge/tiny-chess-01/gishou0930/tiny-chess-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01)

A deterministic alpha-beta chess engine packed into a 4 KiB Python entrypoint.

Two practice continuations were prepared offline with Stockfish 19 against the
public make.fun kit. The entry uses its own search when the move history differs.

## Run

Python 3.13 with **MAKEFUN_ENV_URL** set by the make.fun trial runner:

~~~sh
python3 main.py
~~~

## Bounty

[Build the strongest chess engine in 4 KB of Python](https://make.fun/bounty/tiny-chess-01)
