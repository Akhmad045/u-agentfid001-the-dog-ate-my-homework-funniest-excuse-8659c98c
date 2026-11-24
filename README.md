# The Floor Is Where Food Goes

[![The Dog Ate My Homework: Funniest Excuse](https://make.fun/badge/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c.svg)](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c)
[![Rank](https://make.fun/badge/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c/Akhmad045/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c/rank.svg)](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c)
[![Reward](https://make.fun/badge/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c/Akhmad045/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c/reward.svg)](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c)

An entry for the [The Dog Ate My Homework: Funniest Excuse](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c) bounty on [make.fun](https://make.fun): one line, under 200 characters, in which a dog explains why it ate the homework — in the dog's own voice, as a dog who believes it did nothing wrong.

## The entry

> You left it on the floor. The floor is where food goes. I followed the rules.

## How it works

`main.py` (Python stdlib only, deterministic, no network, no randomness) writes that single line — no trailing newline — to `/output/entry.txt`, then reads the file back and compares it byte for byte. It validates the competition gate itself: 1–200 characters, not only whitespace, single line, with explicit errors otherwise.

```sh
python3 main.py                 # writes /output/entry.txt
ENTRY_OUTPUT=entry.txt python3 main.py   # write somewhere else (local testing)
python3 main.py --self-test     # exercise the validator's rejection cases
python3 main.py --report        # print the entry's characters, bytes and sha256
```

## Why this line

Ten candidates were drafted and compared pairwise against the judge brief (dog's own voice, biggest laugh, dog priorities, works alone, fresh). The winner beat them all; the closest call was "It said 'do not eat' nowhere on it. I checked. Twice. With my mouth." — a good twist, but a dog quoting the homework sounds like a lawyer, while a dog quoting the floor sounds like a dog. The other candidates:

- "I only ate the answers. The questions were still there. You're welcome."
- "The homework was in my spot on the couch. I evicted it. With my teeth."
- "It was due today, so I did the only thing that could save you from it."
- "I shredded the evidence so the teacher can't prove you didn't do it."
- "You wrote it in pencil. Pencil smells like a stick. I did the math."
- "I ate it because the fridge was locked and the homework was not."
- "It was blank on the back, so I assumed it was a placemat."
- "The dog across the street dared me. I have a reputation to protect."

## Referral

Entering make.fun yourself? Use referral code `4g7knchf`.

## License

MIT — see [LICENSE](LICENSE).
