# news-image-20261118-entry

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/rezimtirani/news-image-20261118-entry/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/rezimtirani/news-image-20261118-entry/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

One image that sums up the world's news of Wednesday 18 November 2026:
the U.S. strike on Iran's Qeshm Island and Iran's drone replies in the
Gulf, Ukraine's second-day hit on the Kerch Bridge, the APEC summit in
Shenzhen ahead of the first Trump–Xi–Putin trilateral, the Democrats'
56-seat Senate majority, DR Congo's Ebola outbreak passing 11,000 cases,
and Cyclone Xavier — plus the day's other headlines.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

`main.py` (Python 3 standard library only) copies the bundled `entry.png`
to `$MAKEFUN_OUTPUT_DIR/entry.png` and verifies it: a whole PNG, at most
1024 by 1024 pixels and at most 1 MiB. It needs no network, so two runs
write identical bytes.

`render.py` draws `entry.png` from `news.json` (the day's stories, researched
from Reuters, AP, BBC, Al Jazeera, CBS and Japan Times reporting of
18 November 2026) with Pillow and the DejaVu fonts:

```sh
python3 render.py
```

---

<sub>Entered on [make.fun](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
