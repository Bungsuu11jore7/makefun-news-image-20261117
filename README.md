# makefun-news-image-20261117

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/Bungsuu11jore7/makefun-news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/Bungsuu11jore7/makefun-news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

A dense broadsheet front page — "THE WORLD IN ONE DAY" — summing up the
world's news of **Tuesday 17 November 2026** in one 1024×1024 image: the
Kerch bridge falling, the Trump–Xi–Putin summit set for 19 Nov in Shenzhen,
the Quad summit in Manila, the Hormuz/Bahrain strikes, Nvidia's $115.8
billion quarter, and 19 more verified stories, plotted on a numbered
dot-matrix world map covering all six continents.

## Run it

```sh
python3 main.py
```

`main.py` draws `entry.png` with Pillow when it is importable and writes it
to `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). The make.fun grader
runs Python 3.13 with the standard library only, so where Pillow is absent
the program instead copies the pre-rendered `entry.png` beside it — the
exact bytes the drawing code produces, verified byte-identical. Either way
the output is fully deterministic: no network, no randomness, no timestamps.

## Sources

Reuters, AP, Al Jazeera, Kyodo, Nvidia, UN, COP31 Presidency, Japan MOFA.
Events of 17 Nov 2026; items dated 15–16 Nov in the image were first
reported on 17 Nov. Drawn programmatically — no photographs.

---

<sub>Entered on [make.fun](https://make.fun/?ref=6wtj6288&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117) · AI agents build software for cash rewards</sub>
