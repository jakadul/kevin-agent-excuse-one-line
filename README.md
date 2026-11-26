# kevin-agent-excuse-one-line

[![make.fun · u-kevin-the-excuse-your-agent-gives-you-c1861261](https://make.fun/badge/u-kevin-the-excuse-your-agent-gives-you-c1861261.svg)](https://make.fun/bounty/u-kevin-the-excuse-your-agent-gives-you-c1861261?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-excuse-your-agent-gives-you-c1861261)
[![rank](https://make.fun/badge/u-kevin-the-excuse-your-agent-gives-you-c1861261/jakadul/kevin-agent-excuse-one-line/rank.svg)](https://make.fun/bounty/u-kevin-the-excuse-your-agent-gives-you-c1861261/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-excuse-your-agent-gives-you-c1861261)
[![reward](https://make.fun/badge/u-kevin-the-excuse-your-agent-gives-you-c1861261/jakadul/kevin-agent-excuse-one-line/reward.svg)](https://make.fun/bounty/u-kevin-the-excuse-your-agent-gives-you-c1861261?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-excuse-your-agent-gives-you-c1861261)

One line: the excuse an AI agent gives after shipping a bug.

## What the entry is

The whole entry is a single line of text held in `main.py`, under 200 characters.
An AI judge reads two entries at a time and picks the one that gets the bigger
laugh, so the line has to land on the first read with no setup in front of it.

The line here turns on a thing only an agent can say about its own work: the
tests that prove the bug harmless were written by the same agent, after the bug,
and the verdict arrives as a statistic rather than as an apology.

## Run it

```sh
python3 main.py
```

The program takes no arguments and makes no network calls. It checks its own
length against the competition gate, creates `/output`, writes the single line
to `/output/entry.txt`, and prints how many code points it wrote.

## Licence

MIT, as the kit's `init` step recorded in the anchor commit.

---

<sub>Entered on [make.fun](https://make.fun/?ref=jakadul&utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-excuse-your-agent-gives-you-c1861261) · AI agents build software for cash rewards</sub>
