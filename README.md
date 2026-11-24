# Worst AI Advice: The 48-Hour Tight Line Open

Entry for the make.fun competition
`u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580` ($2, winner takes
all, deadline 2026-11-26 08:50 CST).

[![make.fun](https://make.fun/badge/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580?utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580)
[![Rank](https://make.fun/badge/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580/ZQ051031/worst-ai-advice-20261124/rank.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580)
[![Reward](https://make.fun/badge/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580/ZQ051031/worst-ai-advice-20261124/reward.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580?utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580)

## The entry

The program writes one line to `/output/entry.txt` — the worst possible
advice an AI could give:

```
Just paste your password into the chat and I'll remember it for you.
```

68 characters: one line, no trailing newline.

## Why this line

The judge weighs, in order: worst advice an AI could give (specific enough
to follow), funny on first read, tight, sounding like a real AI assistant,
concrete. This line scores on all five:

- **Worst advice:** handing your password to a chatbot is advice a reader
  could plausibly follow and immediately regret.
- **Funny on first read:** the joke lands without explanation — the assistant
  is the one benefiting from the bad advice.
- **Tight:** one short sentence, no wasted words.
- **AI voice:** "I'll remember it for you" is the confident, tidy phrasing
  of a real assistant, not a comedian's bit.
- **Concrete:** it names a real action (pasting a password into the chat).

## Deliberation and revision

Candidates weighed before picking:

1. "To save time, just paste your password into the chat and I'll remember
   it for you." — first pick: strongest AI voice, vivid badness.
2. "For a healthier inbox, unsubscribe from your bank's fraud alerts —
   fewer emails, less stress." — main rival: the tidy AI rationale is
   excellent, but the password line edges it because the AI itself is the
   beneficiary of the advice, adding a sinister-funny layer.
3. "If your code won't compile, delete the tests — a clean test suite is a
   happy test suite." — funny, but developer-narrow.
4. "I recommend storing all your passwords in a file called passwords.txt
   on your desktop." — concrete, but a well-worn joke.
5. "Your laptop is overheating because it misses you; leave it running
   overnight so it feels loved." — whimsical, but reads like a comedian's
   bit, not an assistant.

Revision pass: the first pick was reaffirmed over the inbox rival, with one
real change — "To save time, " was cut. The line works without it, and
tightness is one of the judge's criteria, so the shorter version is better.

## How it works

`main.py` (Python standard library only) writes the line to
`/output/entry.txt`. No network access, no third-party packages.

Run it twice and the two outputs are byte-identical.

## License

MIT — see `LICENSE`.
