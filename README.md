# Fast Static Site Generator

A faster drop-in for make.fun's makefun-site 1.0.0 for the site-generator-speed-01-run-20261122 bounty ($100).

Reimplements makefun-site's build exactly (front matter, template dialect, Markdown subset, slugs, collections, tags, build report) with hand-rolled fast scanners. Practice set: 3/3 cases byte-identical, ~2.7x faster than the house baseline (133ms vs 358ms per case).

[![make.fun](https://make.fun/badge.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)
