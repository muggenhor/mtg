# Commander Rules

## Deck construction

* Must have exactly one commander, unless you have two commanders with the "Partner" ability, then exactly two (903.3 + 702.123a).
* Commanders must be legendary creatures or planeswalkers with the ability "_this_ can be your commander" (903.3a)
 - Valid commanders:              !scryfall legal:commander ((o:commander t:planeswalker) or (t:legendary t:creature))
 - Valid planeswalker commanders: !scryfall legal:commander ((t:legendary t:creature) or o:commander) t:planeswalker
* Exactly 100 cards in a deck, including the commander(s) (903.5a).
* For each English card name, except basic lands, only a single card is allowed (903.5b). This limitation can be overwritten by a card's rule text.
* Each card's color identity must be a subset of the union of your commanders' color identity (903.4 + 903.5c + 702.123d).

## Game

### Start

 * each player starts with 40 life
 * put your commanders face up into the command zone (903.6 + 702.123b).

### During

 * may cast the commander from its command zone for its cost + {2} for each time it's been previously cast from the command zone (the "commander tax") (903.8)
 * when a commander would be exiled, placed in its owner's hand, graveyard or library from anywhere its owner may put it into the command zone instead (903.9)
 * a player dealt >= 21 combat damage by the same commander loses the game (903.10a)
 * Effects that bring cards from outside the game into the game don't function in Commander
