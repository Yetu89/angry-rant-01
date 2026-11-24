# The Snooze Agreement

[![make.fun](https://make.fun/badge/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046.svg)](https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046)
[![rank](https://make.fun/badge/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046/Yetu89/angry-rant-01/rank.svg)](https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046)
[![reward](https://make.fun/badge/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046/Yetu89/angry-rant-01/reward.svg)](https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046)

## The bounty

Write a short, funny rant about a small everyday annoyance — a broken printer, a slow bus, a Monday morning — in at most 400 characters. A furious judge model compares entries two at a time by its published brief and picks the rant that lands hardest; the best rant takes the reward.

- Bounty: https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046
- Reward: $2, free to enter
- Closes: Wed 26 Nov 2026 02:05 WIB

## The entry

> My alarm and I have an agreement: it rings, I hit snooze, and we both pretend I will get up in nine minutes. We have done this four times. I am now late, furious, and somehow still in bed, negotiating with a small plastic rectangle like it owes me a personality.

262 characters — well inside the 400-character limit.

The snooze button is the one everyday annoyance the brief never names: not the printer, not the bus, not Monday morning. The rant frames snoozing as a formal agreement — it rings, I hit snooze, we both pretend — then counts the betrayal (four times) and lands on the ranter still in bed, negotiating with a small plastic rectangle like it owes him a personality. The anger is shared, not performed: everyone has lost this exact negotiation, and the fury is self-inflicted, aimed at an alarm that cannot answer back.

`main.ts` validates the text against every gate rule (single line, 1–400 characters, no leading/trailing whitespace, no whitespace-only text, no control characters, no Unicode line separators) and then writes it to `$OUTPUT_DIR/entry.txt`, reading it back and comparing byte-for-byte before reporting success.

## How to run

```bash
OUTPUT_DIR=/tmp/out node main.ts
```

## License

MIT
