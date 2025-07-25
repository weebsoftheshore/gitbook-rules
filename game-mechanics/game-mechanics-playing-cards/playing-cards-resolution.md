# Playing Cards - Resolution

Resolution of cards or abilities happens after all costs for playing the card are paid, the card is played, passes legality checks, is placed into the Effects Stack, and no player has taken any player actions or the game state has not changed in a way that would invalidate the card or ability. A card is then resolved when the above conditions are met and while no other game actions are taking place; cards are resolved at discrete points of time within a game, with each card/ability having its own point in time to resolve.

Resolving a card involves performing the actions and applying the effects listed on a card or ability is resolved step-wise, starting from the top of its rules text to the bottom. State-based effects are not checked unless explicitly required by the card. Only after the rules text is resolved will the next state-based check occur.

{% hint style="info" %}
E.g. If an effect says “Glimpse 2. Draw a card,” the player must first Glimpse 2, only after which they can draw a card. No state-based checks occur between each instruction.
{% endhint %}

1. All champions, allies, weapons, items, domains, tokens, and other objects will enter the field or intent under the control of the player who controlled the corresponding card or effect that would generate the object in the Effects Stack
2. “You” printed on a card or implicit in commands are directed to the controller, while other specified players or objects are referenced according to target declarations on activation/materialization.
3. All action cards will resolve from the perspective of the player who controlled the corresponding card in the Effects Stack.
4. All effects will resolve from the perspective of the player who controlled the effect in the Effects Stack.
5. Some effects specify "may" as a permission-based clause during the resolution of an effect or ability. For these effects, the specified player will choose to accept or reject the option offered during the resolution. There is no later point in time at which this decision can be made.
6. As attack cards resolve, the game will check if it is legal for its controller to initiate a combat phase. If it is, the attack card will resolve and enter a player’s champion’s intent from the perspective of the player that controlled the corresponding card in the Effects Stack. If a combat phase cannot be initiated (e.g., an attack card was activated at fast speed during the opponent’s turn), the attack fizzles as a state-based action.
7. If any optional choices are made for any effects during a resolution, such as "you may X" where X is a requirement, cost, or action, the player must completely do X for any related effects to happen; players can't partially fulfill the condition on optional effects. Typically, these effects are tied to a default case of "if you don't," which will automatically be applied if the optional cost/action is not taken.



#### Checking Resolution

Before a card or ability begins resolving, the game will perform a check to make sure that all conditions for successful resolution are met.

1. For champions, a level-check and lineage check will be performed in addition to any other legality checks upon attempted resolution of a champion materialization.
2. If the resolution is deemed illegal in any way, it will instead “fizzle”; if something fizzles any of the effects that would occur during its resolution don't, and it would not become an object, if it were to do so.
3. The phrasing “Up to \[X] target \[object]” on cards and effects is treated as optional conditions and will not impact whether or not a card will resolve correctly. The same is true for wording such as "any number" or "any amount" for chosen targets.
4. Cards and effects that specify and quantify the necessary targets that must be chosen on the declaration of activation or playing of the card must have each of its targets still be valid/legal upon resolution.
   1. A card or effect (such as abilities or attacks) resolves if and only if the targets selected are all still legal targets for the event upon resolution (apart from “Up to \[X]” target phrasings).
   2. If any one of the necessary targets becomes illegal/invalid at the point of resolution, the entire card/effect does not resolve. If a card does not resolve this way, the card is then sent to the graveyard (or, if it is regalia, to banishment).





