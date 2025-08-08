# State-based Checks and Effects

State-based effects occur as a result of conditions in the state of the game being met and often do not require any additional input from the player to be completed.

#### General Rules:

1. Checks to see if state-based conditions are met happen every time the state of the game changes in the time between a player losing or passing Opportunity and the moment at which another player receives Opportunity.



#### Types of Checks

1. Game-ending Checks: The game will first make a pass to validate whether any conditions that result in a player having won or lost a game are to be checked.
2. Damage: If enough damage is marked on a unit to bring that unit’s life to 0 or less, the unit will die.
3. Durability: If a weapon has no durability counters, the weapon will be destroyed.
4. Unique Objects: If a player controls 2 or more unique objects with the same name, the game will force the player to choose one of them to keep, and the player must sacrifice the rest of those objects before the game continues.
5. Copy: If a copy of a card activation is sent to a zone other than the Effects Stack, it will cease to exist unless it has a corresponding card. If a copy of an object is sent to a zone other than the field, it will cease to exist unless the copy has a corresponding card.
6. Clean-Up: The game will remove all ally damage counters, “until end of turn” or one-shot effects, and other temporary conditions at the end of each turn. If any limitations are placed on players, such as maximum hand sizes, the active player must take the necessary actions to fulfill such limitations before the game continues.
7. Combat Roles:  A defending unit is no longer a defender/defending unit as soon as it is no longer an attack target. A retaliating unit stops being a retaliating unit when it no longer has a valid retaliation target.
