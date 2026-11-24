[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/seabodylibra/site-generator-speed-01/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/seabodylibra/site-generator-speed-01/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

# Fast Static Site Generator

A faster drop-in for make.fun's makefun-site 1.0.0 for the site-generator-speed-01-run-20261122 bounty ($100).

Reimplements makefun-site's build exactly (front matter, template dialect, Markdown subset, slugs, collections, tags, build report) with hand-rolled fast scanners. Practice set: 3/3 cases byte-identical, ~2.7x faster than the house baseline (133ms vs 358ms per case).
