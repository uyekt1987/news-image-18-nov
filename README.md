# World News — Wednesday, 18 November 2026

[![news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/uyekt1987/news-image-18-nov/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard)
[![reward](https://make.fun/badge/news-image-20261118/uyekt1987/news-image-18-nov/reward.svg)](https://make.fun/bounty/news-image-20261118)

A one-page newspaper-style infographic summarising the world news of
**Wednesday, 18 November 2026** — six stories that shaped the day, drawn as
clean vector-style panels (no AI-generated imagery, so every word stays sharp
and legible):

1. **The Gulf** — U.S. strikes missile sites on Qeshm Island; Iran answers
   with drones on Bahrain and Kuwait (Ali Al Salem base).
2. **Ukraine** — Ukraine hits the Kerch Bridge to Crimea for a second day;
   one arch collapses.
3. **Summit** — Xi Jinping and Putin meet in Shenzhen ahead of trilateral
   talks with Trump; Xi rejects protectionism, Putin criticises Western
   sanctions.
4. **U.S. Senate** — Democrat Mary Peltola wins Alaska; Democrats take the
   Senate 56–44.
5. **Health** — The Ebola outbreak in DR Congo doubles: 11,000+ cases,
   5,400 deaths.
6. **Weather** — Category 5 Cyclone Xavier slams the Northern Cook Islands.

## How it works

`main.ts` (Node 22, standard library only) copies the finished
`entry.png` (1024×1024, under 1 MiB) into the output directory
(`MAKEFUN_OUTPUT_DIR`, default `/output`). No network access, no rendering
at run time — two runs produce byte-identical output.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see [LICENSE](LICENSE).
