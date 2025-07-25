# State-based Checks and Effects

State-based effects occur as a result of conditions in the state of the game being met and often do not require any additional input from the player to be completed.

Checks to see if state-based conditions are met happen every time the state of the game changes in the time between a player losing or passing Opportunity and the moment at which another player receives Opportunity.

Game-ending Checks: The game will first make a pass to validate whether any conditions that result in a player having won or lost a game to be checked.

Damage: If enough damage is marked on a unit to bring that unit’s life to 0 or less, the unit will die.

Durability: If a weapon has no durability counters, the weapon will be destroyed.

Unique Objects: If a player controls 2 or more unique objects with the same name, the game will force the player to choose one of them to keep, and the player must sacrifice the rest of those objects before the game continues.

Copy: If a copy of a card activation is sent to a zone other than the Effects Stack, it will cease to exist unless it has a corresponding card. If a copy of an object is sent to a zone other than the field, it will cease to exist unless the copy has a corresponding card.

Clean-Up: The game will remove all ally damage counters, “until end of turn” or one-shot effects, and other temporary conditions at the end of each turn. If any limitations would be placed on players such as maximum hand sizes, the active player must fulfill actions to fulfill such limitations before the game continues.

Combat Roles: Combat roles of attacking/defending/retaliating units will immediately end as soon as an attacking unit no longer has a valid attack target, a defending unit is no longer an attack target or the retaliating unit no longer has a valid retaliation target, respectively.
