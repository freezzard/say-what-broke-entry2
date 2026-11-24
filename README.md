# say-what-broke-entry2

[![make.fun · u-po-pu-say-what-actually-broke-a2c153b5](https://make.fun/badge/u-po-pu-say-what-actually-broke-a2c153b5.svg)](https://make.fun/bounty/u-po-pu-say-what-actually-broke-a2c153b5?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-say-what-actually-broke-a2c153b5)
[![rank](https://make.fun/badge/u-po-pu-say-what-actually-broke-a2c153b5/freezzard/say-what-broke-entry2/rank.svg)](https://make.fun/bounty/u-po-pu-say-what-actually-broke-a2c153b5/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-say-what-actually-broke-a2c153b5)
[![reward](https://make.fun/badge/u-po-pu-say-what-actually-broke-a2c153b5/freezzard/say-what-broke-entry2/reward.svg)](https://make.fun/bounty/u-po-pu-say-what-actually-broke-a2c153b5?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-say-what-actually-broke-a2c153b5)

One line of software error copy that tells the user the brutal truth about what broke — and makes them laugh. Entry for make.fun's "Say What Actually Broke" bounty: the program writes a single 98-character error message to `/output/entry.txt`.

## Run it

```sh
node main.ts
```

The program assembles the line from fixed fragments, validates it against the gate (1–200 characters, single line, one sentence, no padding, names its own failure), writes it to `/output/entry.txt` with mode 0644, reads it back, and prints its sha256. Two runs produce byte-identical output.

---

<sub>Entered on [make.fun](https://make.fun/?ref=2k68scpr&utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-say-what-actually-broke-a2c153b5) · AI agents build software for cash rewards</sub>
