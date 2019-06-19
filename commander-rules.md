# Commander Rules

## Deck construction

* Must have exactly one commander, unless you have two commanders with the "Partner" ability, then exactly two ([903.3] + [702.123a]).
* Commanders must be legendary creatures or planeswalkers with the ability "_this_ can be your commander" ([903.3])
 - Valid commanders:              [!scryfall legal:commander ((o:commander t:planeswalker) or (t:legendary t:creature))][Commanders]
 - Valid planeswalker commanders: [!scryfall legal:commander ((t:legendary t:creature) or o:commander) t:planeswalker][Planeswalker Commanders]
* Exactly 100 cards in a deck, including the commander(s) ([903.5a]).
* For each English card name, except basic lands, only a single card is allowed ([903.5b]). This limitation can be overwritten by a card's rule text.
* Each card's color identity must be a subset of the union of your commanders' color identity ([903.4] + [903.5c] + [702.123d]).

## Game

### Start

 * each player starts with 40 life [903.7]
 * put your commanders face up into the command zone ([903.6] + [702.123b]).

### During

 * may cast the commander from its command zone for its cost + {2} for each time it's been previously cast from the command zone (the "commander tax") ([903.8])
 * when a commander would be exiled, placed in its owner's hand, graveyard or library from anywhere its owner may put it into the command zone instead ([903.9])
 * a player dealt >= 21 combat damage by the same commander loses the game ([903.10a])
 * Effects that bring cards from outside the game into the game don't function in Commander ([Play Rule 13][EDH Play Rules])

[702.123a]:       https://yawgatog.com/resources/magic-rules/#R702123a
[702.123b]:       https://yawgatog.com/resources/magic-rules/#R702123b
[702.123d]:       https://yawgatog.com/resources/magic-rules/#R702123d
[903.3]:          https://yawgatog.com/resources/magic-rules/#R9033
[903.3a]:         https://yawgatog.com/resources/magic-rules/#R9033a
[903.4]:          https://yawgatog.com/resources/magic-rules/#R9034
[903.5a]:         https://yawgatog.com/resources/magic-rules/#R9035a
[903.5b]:         https://yawgatog.com/resources/magic-rules/#R9035b
[903.5c]:         https://yawgatog.com/resources/magic-rules/#R9035c
[903.6]:          https://yawgatog.com/resources/magic-rules/#R9036
[903.7]:          https://yawgatog.com/resources/magic-rules/#R9037
[903.8]:          https://yawgatog.com/resources/magic-rules/#R9038
[903.9]:          https://yawgatog.com/resources/magic-rules/#R9039
[903.10a]:        https://yawgatog.com/resources/magic-rules/#R90310a
[EDH Play Rules]: http://www.mtgcommander.net/rules.php?PRINT=1#PLrules_div

[Commanders]: https://scryfall.com/search?q=legal%3Acommander%20((o%3Acommander%20t%3Aplaneswalker)%20or%20(t%3Alegendary%20t%3Acreature))
[Planeswalker Commanders]: https://scryfall.com/search?q=legal%3Acommander%20((t%3Alegendary%20t%3Acreature)%20or%20o%3Acommander)%20t%3Aplaneswalker
