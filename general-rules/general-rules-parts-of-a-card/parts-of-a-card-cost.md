# Parts of a Card - Cost

The basic cost of the card is denoted on the top left corner of a card.&#x20;

Costs are either reserve costs or memory costs; Reserve costs are represented with a yellow color while Memory costs are represented with a blue color.&#x20;

{% hint style="info" %}
A champion’s memory cost is located beneath its printed level.
{% endhint %}

The “cost” of a card when referred to in its rules text refers to the cost type reflected in that card.

If the number is a reserve cost, it represents the number of cards that must be placed into the Memory zone face-down from that player’s hand and [reserved](../../glossary/game-terms.md#reserve) until the next recollection as payment for that cost.&#x20;

{% hint style="info" %}
To pay for a reserve cost, select X other cards from your hand where X is the cost required to activate the desired card and place them into your Memory zone face-down.
{% endhint %}

If the number is a memory cost, the cost must be paid by banishing randomly selected cards from the [Memory zone](../../game-mechanics/game-mechanics-game-zones/game-zones-memory.md).

1. To pay for a Memory cost, X cards are randomly selected from the Memory zone where X is the Memory cost to materialize the desired card.&#x20;
   1. Non-random forms of payment for a given cost are paid before random costs are paid.
2. No Opportunity is given to players and no player actions may be taken between the time cards are chosen for payment of a memory cost and the time at which those cards are banished.

If there are any additional costs for the activation or the materialization of cards or for activating abilities, these must be paid at the same time the normal costs are paid before the card or effect enters the Effects Stack.

If a card or effect would specify a cost as a result of the card resolving, payment of these costs follows the rules text and timing therein.

Effects and abilities can modify costs to be paid.&#x20;

3. To calculate the required cost, simultaneously add the numeric value of any cost increases applied by any modifying effects and subtract the numeric values of any cost decreases applied by any modifying effects. The result is the numeric cost required to be paid.
4. Reduction and increases of costs change the default cost type for cards by reducing or increasing that cost type, respectively. Default costs are reserve costs for main deck cards and memory costs for material deck cards.
5. Costs cannot be reduced below 0. If a cost would be reduced to a number below 0, that cost is set to 0 instead.

If a card has a variable cost represented by X, X is treated as 0 while the card is not on the Effects Stack. Otherwise, X is treated as whichever number was chosen as X as it was placed on the Effects Stack.

6. If a card with a variable cost in the Effects Stack is copied, the copied instance will assume the value of X chosen for the original card.
7. If a card with a variable cost is allowed to be played without paying for its reserve or memory cost, X must be chosen as 0; players may not choose any other values for X in this case.
8. References to the value X as part of the effects of a card or object will be treated as the previously chosen value of X.
9. If an effect copies object on the field with any values of X among its costs or of a previously set value for X, the copy will be made with those values of X set to 0.
