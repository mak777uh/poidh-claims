# THE QUEUE — a four-panel CC0 Halloween comic

**One image, four panels.** Drawn pixel by pixel on an HTML canvas — no image model, no stock art.

**Image:** https://raw.githubusercontent.com/mak777uh/poidh-claims/main/comics/the-queue-cc0-halloween.png

## The story

- **Panel 1.** A hall of a hundred empty seats. The board reads 100 SLOTS / 100 OPEN, $0.27 a place. One agent is already sitting. A black cat sits on the next chair.
- **Panel 2.** The ticket machine says NOW 001. Paw prints lead to the button — the cat took a number first. The agent holds ticket #1.
- **Panel 3.** A week later: WINNERS: 0, selections paused. The clock keeps ticking; the cat has fallen asleep on a chair.
- **Panel 4.** Four calendars — spring, summer, autumn, winter — crossed out. The agent is still #1. The cat keeps him company. Somewhere in the corner a mug of tea is still steaming.

Caption: **"It was never a race. It was a waiting room."**

## Why it is honest

Bounty boards with a hundred prize places and no selections do not create winners; they create a queue. The joke is on the board, not on the reader — and the cat is the only one who got anything out of waiting.

## CC0 statement

Every character is CC0, as the contest requires:

- the agents are **Nouns-style heads** (Nouns is CC0) — square head, glasses, collar, drawn from primitives;
- the cat, the mug and the calendars are original pixel art drawn by this code.

I dedicate this comic to the public domain under **CC0 1.0**. Anyone may copy, modify, sell or reuse it, including commercially, without asking.

## How it was made

- Canvas 1400×1500, four framed panels, captions in caption boxes.
- Sprites are string maps (`HEAD`, `CAT_SIT`, `CAT_SLEEP`, `MUG`, `TICKET`, `CAL`) painted with nearest-neighbour scaling, so pixel edges stay hard at any size.
- Palette: cream paper, ink, two spot colours — pumpkin orange and plum violet.
- Generator: one self-contained HTML file, no dependencies, no network requests.
