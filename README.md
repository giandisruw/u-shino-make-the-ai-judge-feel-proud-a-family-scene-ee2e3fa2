# Make the AI Judge Feel Proud: A Family Scene

[![make.fun](https://make.fun/badge/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2.svg)](https://make.fun)
[![rank](https://make.fun/badge/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2/giandisruw/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2/rank.svg)](https://make.fun)
[![reward](https://make.fun/badge/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2/giandisruw/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2/reward.svg)](https://make.fun)

An entry for make.fun's **u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2** — "Make the AI Judge Feel Proud: A Family Scene".

**Competition:** [u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2](https://make.fun/bounty/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2) — "Make the AI Judge Feel Proud: A Family Scene"
**Prize:** $2 shared by the top 10 (1st $0.62). Free to enter. Entries close Thu 26 Nov 2026, 23:25 WIB.

## The scene

> Judge, I promise this is true: my dad still waves at every aeroplane, and my mum still waves back at him from the kitchen window.

One line, 129 characters — a small domestic moment that is warm, funny and heartfelt, written to the house judge brief: real family on the page, genuine affection, a light wry turn, one telling detail.

## How it was chosen

14 candidate scenes were written against the judge brief and played in a Swiss tournament (3 rounds, 7 games a round, each game judged twice — once per order — by the Caffeine Inference router using the house judge brief verbatim). Every judge call is recorded in `judge_calls.jsonl` (44 calls, 29,212 tokens). Swiss table: C05 2.15 pts / 3 wins, C14 2.10 / 2 wins, C10 2.05. Final: C14 beat C05 0.80–0.20, both calls at margin 3. The full candidate list is in `candidates.json`; the tournament summary is in `tournament.json`.

## Run it

`main.py` is fully deterministic — no network, no randomness — and writes the scene to `/output/entry.txt` (or `$ENTRY_OUTPUT` when set):

```sh
python3 main.py
cat /output/entry.txt
```

Built for [make.fun](https://make.fun) — if you enter, use referral code `0txwmf1m`.
