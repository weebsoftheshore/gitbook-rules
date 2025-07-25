# Game Mechanics - Game Zones

A game zone is a physical zone in the play area where cards are placed. There are 9 total zones in Grand Archive: [Main Deck](game-zones-main-deck.md), [Material Deck](game-zones-material-deck.md), [Hand](game-zones-hand.md), [Memory](game-zones-memory.md), [Field](game-zones-field.md), [Graveyard](game-zones-graveyard.md), [Banishment](game-zones-banishment.md), [Intent](game-zones-intent.md), and the [Effects Stack](game-zones-effects-stack.md).

The Field and Effects stack are the only zones shared by all players and control of specific cards and objects in these zones are specified while in these zones.

Cards in zones can have one of two visibility states: face-up or face-down. Face-up cards present their card front up towards all players whereas face-down cards present their card back up towards all players. Face-down cards typically have hidden information from some or all players in the game.

Cards can only exist in one zone at a time and will always be in a zone during a game. If a card is not in a zone, it is not considered part of the game.

If a card changes zones, it is considered to only be in the zone it was moved to after it is moved.

1. A card’s zone changes only if the destination zone is different from the zone it was moved from.
2. If a card in a private zone is moved to a public zone, it is turned face-up by default. If a card in a public zone is moved to a private zone, it is turned face-down by default.

A card changing zones or object changing zones is considered public information that is passively available to the game state. This information is typically only important when referenced by an effect or ability

{% hint style="info" %}
E.g. If a card enters the Graveyard from the Main Deck, the game will know that this has happened, but it may not be important. If a card or object has a triggered ability in such an event, it will become relevant and the triggered ability will be placed onto the Effects Stack.
{% endhint %}

Some information is carried by cards (or the objects they may become) when a card changes zones.

1. Abilities or effects granted to card activation or the object that card activation would become allow the related information to cross over the last known zone after a zone was changed.
2. Abilities of objects can reference information about the activations that created those objects as they were resolved, including what costs were paid to activate that object and what properties that card activation had as it was resolving.
3. Objects can track and reference the cards that were used to pay for their activation and/or materialization costs.

The list, number, and properties of face-up cards in public zones are countable and itemizable by every player in a game.

The order of cards in every zone except the Main Deck and Effects Stack can be changed; players can’t change the order of cards in the Main Deck or Effects Stack.

If an effect specifies to do an action to a zone, that action affects all cards in that zone equally.

Zones other than the Main Deck and Material Deck generally start the game empty; no cards are in those zones at the start of the game.



The following pages discuss these topics:

* [Public vs Private Information](game-zones-public-vs-private-information.md)
* [Main Deck](game-zones-main-deck.md)
* [Material Deck](game-zones-material-deck.md)
* [Field](game-zones-field.md)
* [Memory](game-zones-memory.md)
* [Graveyard](game-zones-graveyard.md)
* [Banishment](game-zones-banishment.md)
* [Hand](game-zones-hand.md)
* [Effects Stack](game-zones-effects-stack.md)
* [Intent](game-zones-intent.md)
* [Object-Specific Zones](game-zones-object-specific-zones.md)
