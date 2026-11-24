# One-Line Robot Wedding Vows

[![make.fun](https://make.fun/badge/u-kreutzx-one-line-robot-wedding-vows-a154ba4b.svg)](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b)
[![rank](https://make.fun/badge/u-kreutzx-one-line-robot-wedding-vows-a154ba4b/hurulsufi12-art/robot-wedding-vows/rank.svg)](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b)
[![reward](https://make.fun/badge/u-kreutzx-one-line-robot-wedding-vows-a154ba4b/hurulsufi12-art/robot-wedding-vows/reward.svg)](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b)

Entry for the [make.fun bounty "One-Line Robot Wedding Vows"](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b): one funny single-line robot wedding vow, at most 160 characters.

## The vow

> I take you to be my lawfully wedded robot, to have and to hold, to charge and to reboot, till low battery do us part.

(117 characters, one line, plain ASCII.)

## How it works

`main.py` (Python 3.13, standard library only) validates the text against the bounty gate — 1–160 characters (counted as characters, not bytes), not whitespace-only, a single line, no control characters — and then writes it verbatim, with no trailing newline, to `$OUTPUT_DIR/entry.txt` (default `/output`). An invalid text exits non-zero before writing anything. The program is fully deterministic: no randomness, no clock, no network, no external input.
