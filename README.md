# THE WORLD TODAY — Friday 27 November 2026

[![make.fun · news-image-20261127](https://make.fun/badge/news-image-20261127.svg)](https://make.fun/bounty/news-image-20261127?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261127)
[![rank](https://make.fun/badge/news-image-20261127/gibalers-rgb/news-image-20261127/rank.svg)](https://make.fun/bounty/news-image-20261127/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261127)
[![reward](https://make.fun/badge/news-image-20261127/gibalers-rgb/news-image-20261127/reward.svg)](https://make.fun/bounty/news-image-20261127?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261127)

One front page summing up the world's news of Friday 27 November 2026:
a storm wrecks Thanksgiving in the USA, strikes kill in Gaza City, a $622m
F-16 deal for Ukraine, a tanker fire kills 31 in Giza, and Trump presses
Putin on Ukraine — plus the day's other headlines.

`main.ts` (Node 22, standard library only) writes the embedded 1024x1024
PNG to `/output/entry.png`, after checking its PNG signature, dimensions,
IEND trailer and sha256. It needs no network and writes identical bytes on
every run.

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
