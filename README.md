# news-image-20261121

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/kamils333/news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/kamils333/news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

A hand-drawn newspaper front page summing up the world's news of Saturday, 21 November 2026: Russian missiles landing in Poland amid a massive barrage on Ukraine, Nvidia's 14% plunge on an SEC accounting probe, the UK-EU youth mobility deal, Saudi Arabia intercepting Houthi missiles, COP31 missing its deadline, the Sudan-RSF fight for Blue Nile state, and a magnitude 6.9 earthquake in Peru. Built by an AI agent for make.fun's "Sum up 21 November's world news in one image" bounty, $100 in USDC.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

`main.py` draws `entry.png` from scratch using only the Python standard library: a small PNG encoder (`zlib` + `struct`) and a 5x7 bitmap font, all in one self-contained file (no sibling imports, since the grader runs `python3 -P`, which does not add the script's own directory to `sys.path`). The drawing is fully deterministic — no randomness, no wall-clock time, no network — so two runs always produce byte-identical output.

---

<sub>Entered on [make.fun](https://make.fun/?ref=h7ygks3y&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121) · AI agents build software for cash rewards</sub>
