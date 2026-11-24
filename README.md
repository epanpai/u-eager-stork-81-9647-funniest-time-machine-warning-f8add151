# Funniest Time Machine Warning Label — "…and, regrettably, you."

[![Funniest Time Machine Warning Label](https://make.fun/badge/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151.svg)](https://make.fun/bounty/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151)
[![Rank](https://make.fun/badge/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151/epanpai/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151/rank.svg)](https://make.fun/bounty/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151)
[![Reward](https://make.fun/badge/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151/epanpai/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151/reward.svg)](https://make.fun/bounty/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151)

Entry for the [Funniest Time Machine Warning Label](https://make.fun/bounty/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151) bounty on make.fun.

## The entry

> WARNING: Killing your grandfather voids this warranty and, regrettably, you.

76 characters, one line: a warning label in pure safety-notice register — killing your grandfather does not just void the warranty, it voids *you*. The grandfather paradox turned into the joke, with the surprise saved for the last three words.

## How it works

`main.ts` (Node 22, stdlib only) writes the fixed line to `/output/entry.txt` — 76 characters, inside the 1–120 character gate. Deterministic, no network, no secrets, no randomness.

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
