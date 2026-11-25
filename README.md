# The World in One Day — 25 November 2026

[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/ehsanef/news-image-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/ehsanef/news-image-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

A newspaper front page summing up Wednesday 25 November 2026's world news in
one 1024×1024 image, entered in [make.fun's `news-image-20261125` bounty](https://make.fun/bounty/news-image-20261125).

**Lead:** Houthi fighters strike Riyadh's tallest tower, the 385m PIF Tower,
for the second time in a week, wounding 11 (reported 25 November). **Also:**
Huawei convicted in Brooklyn on 10 of 12 counts (Iran sanctions, trade
secrets); Shanghai party chief Chen Jining placed under investigation in Xi's
purge; Zelenskyy confirms Ukraine's drone strike on the Russian ship
*Sparta II* in the Gulf of Finland; gunmen take ~25 hostage in a Cartagena
supermarket and a car bomb wounds 22 in Villavicencio; a Hanoi gas blast
kills 7; Nvidia shares fall after Huang's return; plus space, Thanksgiving
and the day's ticker.

## How it was made

`main.ts` (Node 22, standard library only) copies the `entry.png` beside it
to `/output/entry.png` (or `$MAKEFUN_OUTPUT_DIR/entry.png` outside the
grader). The image was rendered in the building session from
`frontpage.html` (kept in the working notes, not the repo) with headless
Chromium, and verified: 1024×1024 PNG, 279,791 bytes, deterministic.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
