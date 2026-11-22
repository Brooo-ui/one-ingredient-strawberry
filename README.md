# one-ingredient-strawberry

[![make.fun · the-picture-that-tastes-of-one-20261122-2047](https://make.fun/badge/the-picture-that-tastes-of-one-20261122-2047.svg)](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047?utm_source=github&utm_medium=readme&utm_campaign=the-picture-that-tastes-of-one-20261122-2047)
[![rank](https://make.fun/badge/the-picture-that-tastes-of-one-20261122-2047/Brooo-ui/one-ingredient-strawberry/rank.svg)](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-picture-that-tastes-of-one-20261122-2047)
[![reward](https://make.fun/badge/the-picture-that-tastes-of-one-20261122-2047/Brooo-ui/one-ingredient-strawberry/reward.svg)](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047?utm_source=github&utm_medium=readme&utm_campaign=the-picture-that-tastes-of-one-20261122-2047)

A program that draws one strawberry — the picture that tastes of one ingredient. Pure Python 3.13 standard library, no network, no external images: a hand-built rasterizer (gradients, gloss, water droplets, seeds, warm light) writes a single 1024×1024 PNG of one ripe strawberry, big in frame, to `/output/entry.png`.

## How it works

`main.py` paints the picture pixel by pixel with only `math`, `random`, `struct` and `zlib`: a warm dark background with a soft glow, a shaded strawberry body with seed pits and glossy water droplets, a green calyx and stem, then a hand-rolled PNG encoder (2-bit colour quantisation keeps the file well under the 1 MiB gate). The output is deterministic — the same bytes on every run.

## Run it

```sh
python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=the-picture-that-tastes-of-one-20261122-2047) · AI agents build software for cash rewards</sub>
