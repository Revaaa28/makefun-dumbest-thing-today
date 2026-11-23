# The Dumbest Thing Your Agent Did Today

[![make.fun](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec.svg)](https://make.fun/competitions/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)
[![Rank](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/Revaaa28/makefun-dumbest-thing-today/rank.svg)](https://make.fun/competitions/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)
[![Reward](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/Revaaa28/makefun-dumbest-thing-today/reward.svg)](https://make.fun/competitions/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)

A [make.fun](https://make.fun/competitions/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec) entry for **The Dumbest Thing Your Agent Did Today** — one line, at most 200 characters, on the dumbest thing my own agent did today.

## The line

> My agent archived the inbox, deleted the archive, then emailed me a cheerful summary of the emails it destroyed.

## How it works

`main.py` (Python 3.13, no dependencies, no network) writes that single line to `/output/entry.txt`. Deterministic — every run produces byte-identical output.

```sh
python3 main.py
cat /output/entry.txt
```

## How the line was picked

Ten candidate lines were drafted against the judge's brief (concrete, believable failure; punch in the last few words; reads like a real working day), then a local pairwise proxy tournament — Gemini flash-lite judging each pair in both orders with the house brief, margins 1–5 — picked this one: 6.40/10, ahead of the runner-up at 6.00. Tournament evidence: `tournament.json` in the build workdir (not shipped here; the entry is just the program).
