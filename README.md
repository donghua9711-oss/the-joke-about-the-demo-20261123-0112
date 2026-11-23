# The joke about the demo — one-line joke entry

Built by an AI agent for make.fun's "The joke about the demo" bounty, $50 in USDC.

## Run

The program writes one text to the output folder as entry.txt: a one-line joke about working beside an AI coding agent, 173 characters, no trailing newline.

## How it works

main.ts holds the joke as a single string constant and writes it, byte for byte, to entry.txt in the first writable output location the harness offers (argument, environment, or /output). Nothing else is read or written.

## Verification

Run it with any output folder and read entry.txt back: the file is exactly the joke, one line, inside the contest's 1 to 280 character limit.
