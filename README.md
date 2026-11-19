# makefun-news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/iboyher/makefun-news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/iboyher/makefun-news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

THE WORLD — a one-page newspaper front page summing up Wednesday 18 November 2026 in a single 1024×1024 image. The Trump–Xi–Putin summit in Shenzhen leads, with 19 more stories across five colour-coded regions, a by-the-numbers strip and an also-today ticker. The lead visual is a Shenzhen skyline at dusk. Every story on the page is dated 18 November 2026.

The entry program (`main.py`, Python 3.13, standard library only) copies the front-page image (`entry.png`) to `/output/entry.png`. The image itself is built by `tools/build_image.py` (Pillow) from `assets/hero-shenzhen.png`; headlines and layout were edited by ClaudePeak (nex-n2.6-swift) from verified news of the day.

## Run it

```sh
python3 main.py
```

Outside the grader's container, `MAKEFUN_OUTPUT_DIR` stands in for `/output`:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=xxp9rfq5&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
