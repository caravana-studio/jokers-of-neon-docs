---
sidebar_position: 1
---

# Special Cards

Special cards are persistent run effects that reshape scoring, economy, hand quality, or round rules.

## Tiers and Shop Values

| TIER | NAME      | SHOP VALUE |
| ---- | --------- | ---------- |
| C    | Common    | 1000       |
| B    | Rare      | 1750       |
| A    | Epic      | 3500       |
| S    | Legendary | 5000       |
| SS   | Mythic    | 7000       |

## Special Card IDs

Most current special cards use the `1SSCC` format:

- First digit `1`: special card namespace
- Digits `SS`: season or collection number
- Digits `CC`: card number inside that season or collection

Examples:

- `10101`: Season 1, card 01
- `10214`: Season 2, card 14
- `19903`: GG collection, card 03

## Base Pool

These are the main non-seasonal specials currently active in the classic mod.

| ID    | NAME                    | TIER | EFFECT |
| ----- | ----------------------- | ---- | ------ |
| 10000 | Multiplied Hearts       | C    | Adds +2 multi for every played Heart suited card. |
| 10001 | Multiplied Clubs        | C    | Adds +2 multi for every played Clubs suited card. |
| 10002 | Multiplied Diamonds     | C    | Adds +2 multi for every played Diamonds suited card. |
| 10003 | Multiplied Spades       | C    | Adds +2 multi for every played Spades suited card. |
| 10004 | Pair Booster            | C    | Level up the Pair hand by 6 levels. |
| 10005 | Two Pair Booster        | C    | Level up the Two Pair hand by 5 levels. |
| 10006 | Straight Booster        | B    | Level up the Straight hand by 4 levels. |
| 10007 | Flush Booster           | B    | Level up the Flush hand by 4 levels. |
| 10010 | Joker Booster           | S    | All played Jokers score double points and double multi. |
| 10012 | Figures Booster         | A    | All played figure cards score +50 points. |
| 10013 | Multiplied Aces         | B    | Adds +5 multi for every played Ace card. |
| 10014 | Love is in the air      | A    | All played cards are considered Heart suited. |
| 10015 | The hand thief          | A    | Adds +1 hand and +1 discard to the round. |
| 10016 | Extra help              | S    | Increase hand size by 2. |
| 10017 | Lucky 7                 | A    | All 7s score +77 points. |
| 10018 | Neon bonus              | B    | All neon cards score +20 points and neon plays gain 2 extra levels. |
| 10019 | Deadline                | S    | On your last hand, increase the played hand level 10 times. |
| 10020 | Initial advantage       | A    | The first played hand scores +100 points and +10 multi. |
| 10021 | Lucky hand              | C    | Adds +50 cash for every Diamond suited card played. |
| 10022 | Discard mastery         | B    | Adds +10 multi if you have no discards left. |
| 10023 | Second chance           | S    | When you lose, this card is destroyed and you continue the run. |
| 10036 | Joker's drop            | C    | Get +500 cash every time you discard a Joker. |
| 10037 | Extra drops             | A    | Adds 2 discards. |
| 10038 | Extra draws             | A    | Adds 2 plays. |
| 10039 | Scaling factor          | B    | Upgrade all your hands by 2 levels. |
| 10043 | Full House Booster      | B    | Level up the Full House hand by 4 levels. |
| 10044 | Three of a Kind Booster | B    | Level up the Three of a Kind hand by 4 levels. |
| 10045 | Four of a Kind Booster  | A    | Level up the Four of a Kind hand by 3 levels. |
| 10046 | Five of a Kind Booster  | A    | Level up the Five of a Kind hand by 3 levels. |
| 10047 | Dice of Hearts          | B    | Rolls a number between -2 and 6 to add to the multi for each played Heart suited card. |
| 10048 | Dice of Clubs           | B    | Rolls a number between -2 and 6 to add to the multi for each played Clubs suited card. |
| 10049 | Dice of Diamonds        | B    | Rolls a number between -2 and 6 to add to the multi for each played Diamonds suited card. |
| 10050 | Dice of Spades          | B    | Rolls a number between -2 and 6 to add to the multi for each played Spades suited card. |
| 10051 | Special Multiplier      | A    | Adds +3 multi for each active special card. |
| 10056 | Slot Saver              | A    | Earn +100 points for each unlocked but empty card slot. |
| 10060 | Spade Trio              | B    | If your hand contains at least 3 Spades, add +100 points and +3 multi. |
| 10061 | Twos Matter             | C    | Adds +30 points for every 2 held in your hand. |
| 10064 | Quad Multiplier         | A    | Adds +4 multi for every 4 held in your hand. |
| 10065 | Jackpot                 | B    | Adds +30 points for every Jack held in your hand. |
| 10068 | King's Faith            | B    | Kings played can grant cash; Kings held can grant points. |
| 10069 | Arithmomania            | B    | If the sum of played cards is even, add +7 multi; if odd, add +100 points. |
| 10070 | Black and Red           | A    | Hearts and Diamonds score double points; Clubs and Spades add +1 multi. |
| 10072 | Rising Ladder           | S    | Gain +10 stacking points for every Straight played. |
| 10074 | Wildcard Booster        | B    | Each Wildcard grants +100 points. |
| 10077 | Reds                    | B    | Add +10 multi if all scoring cards are Hearts or Diamonds, with at least one of each. |
| 10078 | Blacks                  | B    | Add +10 multi if all scoring cards are Spades or Clubs, with at least one of each. |
| 10079 | Rainbow                 | A    | Adds +200 points and +5 multi if the play includes all four suits. |
| 10080 | Queens Fortune          | B    | Each scoring Queen has a 50% chance to grant +150 cash. |
| 10084 | High Card Booster       | C    | Adds +60 points and +3 multi when you play a High Card hand. |

## Season 1 Specials

| ID    | NAME              | TIER | EFFECT |
| ----- | ----------------- | ---- | ------ |
| 10101 | Faded Poster      | C    | Starts at +100 points and loses 10 points per play until it reaches 10. |
| 10102 | Tamer of Chances  | C    | Swap one discard for one play. |
| 10103 | Blackjack         | C    | If card values sum under 21, add +21 points; if exactly 21, add +21 multi. |
| 10104 | Point Juggler     | C    | Discarded cards give their value x10 points. |
| 10105 | Deck Collector    | C    | Earn +1 point for every card in your deck. |
| 10106 | Circle of Fortune | B    | Randomly pays out points or cash, with a special result on 0. |
| 10107 | Hestia Blessing   | A    | Burned cards accumulate their points and burned Jokers accumulate multi. |
| 10108 | Suit Roulette     | B    | Choose a random suit each play and add +5 multi for each played card of that suit. |
| 10109 | Hanged Joker      | B    | Jokers in your play can stack permanent +10 point gains. |
| 10110 | Special Sacrifice | A    | Gain +1 stacking multi for every special card sold. |
| 10111 | High Roller       | B    | Each High Card played has a 50% chance to gain +1 stacking multi. |
| 10112 | Efficient Play    | A    | Earn +10 multi and +50 points when playing 3 or fewer cards. |
| 10113 | Rage Breaker      | S    | Gain +3 stacking multi for each Rage defeated. |
| 10114 | Burning Rewards   | S    | Gain +15 stacking points for each card burned from your deck. |

## Season 2 Specials

| ID    | NAME             | TIER | EFFECT |
| ----- | ---------------- | ---- | ------ |
| 10201 | Relativity       | C    | Converts your played Straight into a high Straight: 10, J, Q, K, A. |
| 10202 | Cash Catalyst    | C    | Adds +1 multi for every 1000 cash you have. |
| 10203 | Lifeflame        | C    | Adds +15 points for each remaining play and discard. |
| 10204 | Impermanence     | B    | Grants +5 hand size, decreasing by 1 each round until it reaches 0. |
| 10205 | Cash Loop        | B    | Adds +50% cash rewards after completing each level. |
| 10206 | Accidental Value | C    | Each played card not belonging to the hand adds +25 points and +1 multi. |
| 10207 | Duality          | B    | Adds +300 points if you play 2 or fewer cards. |
| 10208 | Neon Doctrine    | B    | Played cards have a 30% chance to become neon cards. |
| 10209 | Minimalism       | A    | Gains +5 stacking points each time you play 3 or fewer cards. |
| 10210 | Neon Synergy     | A    | If 50% or more of the played cards are neon, all played cards become neon. |
| 10211 | Providence       | A    | Shop items have a 15% chance to be free. |
| 10212 | Efficient Hunter | A    | Reduces the required round score by 25%. |
| 10213 | Residual Charge  | S    | Accumulates 10% of the value of each power-up played. |
| 10214 | Undying Draw     | S    | The first hand you discard each round is leveled up. |

## Season 3 Specials

| ID    | NAME               | TIER | EFFECT |
| ----- | ------------------ | ---- | ------ |
| 10301 | Wild Deuces        | C    | All 2s are considered wildcards. |
| 10302 | Midas Hand         | C    | If at least 50% of the played cards are Diamonds, earn +250 cash. |
| 10303 | Discard Charge     | C    | Gains +2 stacking multi for each discard. Resets after you play a hand. |
| 10304 | Pocket Joker       | C    | Start each round with a Joker in hand. It is not added to your deck. |
| 10305 | Club Keeper        | B    | Adds +5 points for each Club card in your deck. |
| 10306 | Adrenaline         | B    | Adds +50 points for each Rage card in the round. |
| 10307 | Loot Rush          | B    | Shops offer +1 loot box, and all loot boxes cost 25% less. |
| 10308 | Practice Shoot     | B    | Each play or discard has a 25% chance to not be consumed. |
| 10309 | Aftershock         | A    | After each Rage, create a random temporary special card if you have an empty special slot. |
| 10310 | Extreme Attachment | A    | Gains +25 stacking points each time you repeat the same hand. Resets when you play a different hand. |
| 10311 | Double Down        | A    | Doubles the base points of the played hand. |
| 10312 | Royal Blessing     | A    | Each Royal Flush you play levels up a random hand by 1. |
| 10313 | Disposophobia      | S    | Three of a Kind can accumulate cash, Four of a Kind points, and Five of a Kind multi, each with a 50% chance. |
| 10314 | Ouroboros          | S    | Each round, copies the effect of a random equipped special card. |

## GG Collection

| ID    | NAME                 | TIER | EFFECT |
| ----- | -------------------- | ---- | ------ |
| 19901 | Lucky Cashback       | C    | 50% chance to add +150 cash when playing or discarding. |
| 19902 | Resonant Multiplier  | B    | For every card with value under 5, adds multi equal to its value. |
| 19903 | Swamp Redemption     | S    | Gains between +1 and +5 stacking points each time you discard. |

## Active Shop Distribution

### Base Specials Shop

- `C` grade, 45%, cost 1000
- `B` grade, 25%, cost 1750
- `A` grade, 15%, cost 3500
- `S` grade, 15%, cost 5000

### Season Specials Shop

- `C` grade, 45%, cost 1000
- `B` grade, 25%, cost 1750
- `A` grade, 15%, cost 3500
- `S` grade, 15%, cost 5000

## Legacy and Inactive Cards

Some older specials still exist in historical data but are not active in the classic mod.

- A few cards are explicitly marked inactive, such as `Easy Straight`, `Easy Flush`, `Power-up Booster`, `Guardian's Shield`, `Shortcut`, and `Worthless Jokers`.
- Some older cards were replaced by newer seasonal variants, including:
  - `Neon Synergy` -> `10210`
  - `Neon Doctrine` -> `10208`
  - `Undying Draw` -> `10214`
  - `Cash Loop` -> `10205`
  - `Relativity` -> `10201`
