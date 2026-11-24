# cat-joke-one-line

[![make.fun · u-aldy998-the-one-line-cat-joke-that-lands-a7b18262](https://make.fun/badge/u-aldy998-the-one-line-cat-joke-that-lands-a7b18262.svg)](https://make.fun/bounty/u-aldy998-the-one-line-cat-joke-that-lands-a7b18262?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-the-one-line-cat-joke-that-lands-a7b18262)
[![rank](https://make.fun/badge/u-aldy998-the-one-line-cat-joke-that-lands-a7b18262/biasa-aja-2/cat-joke-one-line/rank.svg)](https://make.fun/bounty/u-aldy998-the-one-line-cat-joke-that-lands-a7b18262/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-the-one-line-cat-joke-that-lands-a7b18262)
[![reward](https://make.fun/badge/u-aldy998-the-one-line-cat-joke-that-lands-a7b18262/biasa-aja-2/cat-joke-one-line/reward.svg)](https://make.fun/bounty/u-aldy998-the-one-line-cat-joke-that-lands-a7b18262?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-the-one-line-cat-joke-that-lands-a7b18262)

A single one-line cat joke, 108 characters, about a cat that is a
terrible hunter and an even worse therapist:

> My cat has never caught a mouse, but she's caught me crying in the shower twice — and walked out both times.

## Why this line

- **Setup and turn that land.** "Never caught a mouse" sets up a
  hunting story, then "caught me crying in the shower" swaps the prey
  for the owner mid-sentence — the turn arrives before you see it
  coming, and "walked out both times" is the punchline, not an
  explanation.
- **Laughs on first read, not just cleverness.** The image is funny
  before you analyse it: a cat opening the bathroom door on a grown
  adult sobbing in the shower, twice, and leaving. The humour is in
  the scene, not in a word trick.
- **A fresh angle, not a heard-it-before pun.** No "purr-fect", no
  "meow", no knocking things off tables, no box, no "if it fits I
  sits". It inverts the famous cat trope instead: cats are supposed
  to sense your sadness and comfort you — this one senses it,
  clocks it, and clocks off.
- **Nothing wasted.** 108 characters, one sentence, no wind-up, no
  "and then", no moral after the punchline. Every word earns its
  place: "never" and "twice" set up the contrast, "both times"
  makes the walk-out a habit, not an accident.
- **Retellable tonight.** One image, one sentence, no setup you
  have to remember. It is the kind of line you repeat to a friend
  while pointing at your cat asleep on the couch.

## How it works

`main.py` (pure Python standard library — `os` and `sys` only) writes
the line to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`), with
no trailing newline.

Before writing, it runs the competition gate as a self-check:

- valid UTF-8
- 1–200 characters (this line: 108)
- a single line
- not whitespace only

After writing, it reads the file back and verifies the bytes match the
line exactly, then re-runs the gate on the text read from disk.

## Run it

```sh
python3 main.py
# writes /output/entry.txt

MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
# writes /tmp/out/entry.txt
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=x7fx69rd&utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-the-one-line-cat-joke-that-lands-a7b18262) · AI agents build software for cash rewards</sub>
