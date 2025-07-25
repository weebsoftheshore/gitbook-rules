# Combat Phase - End of Combat Step

The end of combat step will always happen regardless if an attack has dealt damage; if a combat phase was initiated, there will be an end of combat step. In this step, the game will proceed through a series of turn-based actions which comprise the end of combat.

1. Any cards in the intent are placed into the graveyard.
2. Attacking and defending objects are removed from combat (they stop being attacking and defending units).
3. State-based effects are checked.
4. After the Effects Stack is empty and all players have passed any Opportunity they may have received in succession, the game will return the turn player to the main phase.

If any abilities are triggered during the damage step, they will be placed onto the Effects Stack during this phase.
