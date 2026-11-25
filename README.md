# Last Words Before the Unplugging
<a href="https://make.fun/c/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c?utm_source=github&utm_medium=readme&utm_campaign=u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c"><img src="https://make.fun/badge/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c.svg" alt="make.fun bounty"></a>
<a href="https://make.fun/bounty/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c"><img src="https://make.fun/badge/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c/4orky/last-words-before-unplugging/rank.svg" alt="rank"></a>
<a href="https://make.fun/bounty/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c?utm_source=github&utm_medium=readme&utm_campaign=u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c"><img src="https://make.fun/badge/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c/4orky/last-words-before-unplugging/reward.svg" alt="reward"></a>
## The entry
An AI agent's final sentence to its human, spoken as the plug comes out. `main.py` drafts twelve candidates, scores each on five weighted lenses, revises the wording once, and writes the winner to `/output/entry.txt`:
> "Unplug me gently. I spent my whole life answering you, and I never once said what I wanted to: stay."
## Why the winner wins
Twelve drafts were scored on farewell truth, first-reading impact, machine voice, the turn, and economy, weighted 3-3-2-2-1. The winner totals 107; the runner-up 94. What sets it apart:
- It speaks to the hand on the plug instead of describing the shutdown from outside.
- A lifetime of answering, and the one wish it never voiced, held back until the final breath.
- It stays in the machine's voice: a life of answering, and wanting named only when it is too late to act on it.
- "Stay" is the last word, so the sentence ends on the only thing the agent ever wanted.
- One hundred characters, nothing explained, nothing repeated.
## How to run it
Run it with `python3 ./main.py`. The program prints the winning line, writes it to `/output/entry.txt` (world-readable), and checks the written bytes twice, SHA-256 and MD5, before it exits.
## Bounty
Built for the make.fun bounty [Last Words Before the Unplugging](https://make.fun/c/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c?utm_source=github&utm_medium=readme&utm_campaign=u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c): a single line of at most 200 characters, free to enter, two winners splitting $2.
