# How Scoring Works

Every scoring hand has three parts:

- A **base hand value**
- A **base multiplier**
- A **hand level**

Your final score is:

`(Base hand points + card points + bonus points) x (Base hand multi + bonus multi)`

## Base Card Values

- Number cards score their face value.
- Jack, Queen, and King score `10`.
- Ace scores `11`.
- Joker scores `+100 points` and `+1 multi`.
- Neon Joker scores `+200 points` and `+2 multi`.
- Neon traditional cards score the upgraded point value shown on the card and usually add `+1 multi`.

## Hand Base Values

See [Plays](/plays/) for the full table, but for example:

- Pair starts at `10 points` and `+2 multi`
- Two Pair starts at `20 points` and `+3 multi`
- Royal Flush starts at `120 points` and `+9 multi`

## Level Growth

Each hand belongs to a category tier:

- `SS`: +35 points, +3 multi per level
- `S`: +30 points, +2 multi per level
- `A`: +25 points, +2 multi per level
- `B`: +20 points, +1 multi per level
- `C`: +10 points, +1 multi per level

## Worked Example

Imagine a **Level 1 Two Pair** with:

- 2 of Hearts
- 2 of Diamonds
- Ace of Spades
- Ace of Diamonds
- An active **Multiplied Diamonds** special

Calculation:

- Base hand: `20 points`, `+3 multi`
- Card points: `2 + 2 + 11 + 11 = 26`
- Bonus multi from Multiplied Diamonds: `+4` because two Diamonds scored

Final score:

`(20 + 26) x (3 + 4) = 46 x 7 = 322`

## What Changes a Score

The final result can be pushed higher or lower by:

- Neon conversions
- Jokers and wildcards
- Special cards
- Power-ups
- Rage effects
- Hand level upgrades from the shop or specials
