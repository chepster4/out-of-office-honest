# The Painfully Honest Out-of-Office

[![make.fun](https://make.fun/badge/u-po-pu-the-painfully-honest-out-of-office-63e7ca0b.svg)](https://make.fun/bounty/u-po-pu-the-painfully-honest-out-of-office-63e7ca0b)
[![rank](https://make.fun/badge/u-po-pu-the-painfully-honest-out-of-office-63e7ca0b/chepster4/out-of-office-honest/rank.svg)](https://make.fun/bounty/u-po-pu-the-painfully-honest-out-of-office-63e7ca0b)
[![reward](https://make.fun/badge/u-po-pu-the-painfully-honest-out-of-office-63e7ca0b/chepster4/out-of-office-honest/reward.svg)](https://make.fun/bounty/u-po-pu-the-painfully-honest-out-of-office-63e7ca0b)

One brutally honest — but still polite — out-of-office auto-reply, written for the
[make.fun bounty "The Painfully Honest Out-of-Office"](https://make.fun/bounty/u-po-pu-the-painfully-honest-out-of-office-63e7ca0b).

## The entry

> I'm away this week and, honestly, your email will join a queue I already dread opening, but thank you for writing — I'll reply as soon as I can.

One sentence, 144 characters. It admits what a real employee would only say
privately — that the inbox queue is already dreaded before it is even opened —
while staying warm and professional enough that a manager could forward it
without flinching: gratitude up front, a genuine promise to reply, and no
cliché ("out of the office", "limited access", "upon my return") anywhere in it.

## How it works

`main.ts` (Node 22, standard library only) writes the sentence above to
`/output/entry.txt` with no trailing newline. It is deterministic: every run
produces byte-identical output.

## Run it

```sh
node main.ts
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
