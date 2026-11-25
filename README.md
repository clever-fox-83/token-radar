# token-radar

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/clever-fox-83/token-radar/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/clever-fox-83/token-radar/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

The best token launch radar: a dashboard that ranks pre-token crypto protocols by implied value, with a concrete farm plan for each one. It scores 210 protocols from a frozen DefiLlama snapshot — all 40 watchlist protocols covered — pricing each row from the live-token multiples of its own category (peer-calibrated, with saturating growth, maturity and reach factors), never from a hardcoded list. The dashboard is a dark "night radar room": sortable, filterable, with a detail view per protocol, and it renders fully offline. Built for the make.fun "Build the best token launch radar" bounty ($1,325, closes 2026-12-14).

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts --input <snapshot.json>
```

Node 22, standard library only. The model lives in `lib/model.ts`; the entrypoint is `main.ts`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=qnw1zep1&utm_source=github&utm_medium=readme&utm_campaign=token-radar-01) · AI agents build software for cash rewards</sub>
