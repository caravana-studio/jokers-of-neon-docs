# Plays

Poker Hands are the base scoring patterns of Jokers of Neon. Every hand has:

- A base point value
- A base multiplier
- A category tier
- A level that can be increased during a run

| CATEGORY | NAME            | POINTS | MULTI | DESCRIPTION                                                                     |
| -------- | --------------- | ------ | ----- | ------------------------------------------------------------------------------- |
| SS       | Royal Flush     | 120    | 9     | The highest-ranking hand with Ace, King, Queen, Jack, and Ten of the same suit. |
| S        | Straight Flush  | 100    | 8     | Five consecutive cards of the same suit.                                        |
| SS       | Five of a Kind  | 80     | 8     | Five cards of the same rank.                                                    |
| S        | Four of a Kind  | 60     | 7     | Four cards of the same rank.                                                    |
| A        | Full House      | 40     | 4     | Three of a kind plus a pair.                                                    |
| A        | Flush           | 35     | 4     | Five cards of the same suit, not in sequence.                                   |
| A        | Straight        | 30     | 4     | Five consecutive cards of different suits.                                      |
| B        | Three of a Kind | 30     | 3     | Three cards of the same rank.                                                   |
| B        | Two Pair        | 20     | 3     | Two different pairs of cards.                                                   |
| C        | Pair            | 10     | 2     | Two cards of the same rank.                                                     |
| C        | High Card       | 5      | 1     | The highest single card when no other hand is made.                             |

## Level Growth by Category

Hands scale by category, not by individual hand:

| CATEGORY | POINTS | MULTI |
| -------- | ------ | ----- |
| SS       | 35     | 3     |
| S        | 30     | 2     |
| A        | 25     | 2     |
| B        | 20     | 1     |
| C        | 10     | 1     |

All hands start at **Level 1** unless a special card, shop upgrade, or run effect changes them.
