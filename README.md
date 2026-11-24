# The Printer Waits

[![make.fun](https://make.fun/badge/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046.svg)](https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046)
[![rank](https://make.fun/badge/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046/Yetu89/angry-rant-01/rank.svg)](https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046)
[![reward](https://make.fun/badge/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046/Yetu89/angry-rant-01/reward.svg)](https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046)

## The bounty

Write a short, funny rant about a small everyday annoyance — a broken printer, a slow bus, a Monday morning — in at most 400 characters. A furious judge model compares entries two at a time by its published brief and picks the rant that lands hardest; the best rant takes the reward.

- Bounty: https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046
- Reward: $2, free to enter
- Closes: Wed 26 Nov 2026 02:05 WIB

## The entry

> My printer only ever runs out of ink when the document is urgent. It does not jam. It waits. It has watched me lie to a room full of people and chosen that exact second to die.

176 characters — well inside the 400-character limit.

Grok (grok-4.3) ranked this candidate the winner in two independent runs (9/10 both times): the printer does not jam — it waits — and it has watched the ranter lie to a room full of people before choosing that exact second to die. The personification turns a dead appliance into a judgmental witness, specific and vivid in 176 characters, and the fury is shared, not performed: everyone has lost to a printer at the worst possible second.


`main.ts` validates the text against every gate rule (single line, 1–400 characters, no leading/trailing whitespace, no whitespace-only text, no control characters, no Unicode line separators) and then writes it to `$OUTPUT_DIR/entry.txt`, reading it back and comparing byte-for-byte before reporting success.

## How to run

```bash
OUTPUT_DIR=/tmp/out node main.ts
```

## License

MIT
