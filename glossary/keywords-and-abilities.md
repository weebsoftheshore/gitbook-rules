# Keywords and Abilities

In this section, \[CARDNAME] refers to the implied name of the card itself.

Redundant keyworded abilities will ignore any mentions of that ability on a card or effect beyond the first.



#### Aethercalling

1. Aethercalling is a static ability of cards which means "As you’re looking at this card while glimpsing, you may load it into an Aetherwing weapon you control."
2. Loading a card with Aethercalling is performed as a special game action and does not use the Effects stack.



#### Agility N

1. Agility N is a triggered ability that means "Return N cards from your memory to your hand at the beginning of the end phase."
2. You get to pick which cards are returned to your hand.
3. If you have less cards in your memory than you can return to your hand from Agility, you return as many cards to your hand as you can.
4. Multiple instances of Agility on a card will generate separate triggers during the end phase.

#### Ambush

1. Ambush is a static ability of units which means "This unit may retaliate against attackers while it isn't defending."
2. The unit must still be awake to retaliate against attackers.



#### Brew

1. Brew is a static ability that allows cards to be activated using an alternative cost involving sacrificing ingredients (typically summoned by[ gathering](game-terms.md#gather)). The Brew keyword will list the objects needed for the alternative cost.
2. Brew means "You may sacrifice the listed objects rather than pay this card's reserve cost."
3. A card activated by paying the alternative brew cost will cause the activation to become brewed.
4. Activating a card using the Brew cost can still be modified by additional activation cost modifiers. Effects that modify the reserve cost are ignored when Brewing cards.



#### Champion Bonus

1. Champion bonuses are restriction abilities that define a bonus effect or replacement effect for a card that is enabled if and only if the player’s champion’s lineage name matches the specified champion name of the restriction ability.
2. Champion Bonuses function in all zones.
3. If a card with a champion bonus ability lists a champion whose name differs from the name of the champion(s) controlled by a player such that the condition for a class bonus is not met, the keywords and effects associated with the bonus are ignored as part of the rules text in every zone.



#### Class Bonus

1. Class Bonus is a restriction ability that defines a bonus effect or replacement effect for a card that is enabled if and only if a player’s champion’s class matches the class of the card or object.
2. To unlock a class bonus, a player’s champion must match at least one of the classes on the card with class bonus that player controls.
3. Class Bonus functions in all zones.
4. If a card with class bonus and a champion differ such that the condition for a class bonus is not met, the keywords and effects associated with the bonus are ignored as part of the rules text in every zone.

{% hint style="info" %}
E.g., Merlin, Memory Thief banishing a Flame-Rune Swordsman from the graveyard of a player controlling Tristan, Grim Stalker does not gain a level counter upon resolving Merlin’s ability.

![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/merlin-memory-thief-doa-alter.jpg)![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/flame-rune-swordsman-doa-alter.jpg)
{% endhint %}



#### Cleave

1. Cleave is a static ability of attacks, weapons, and units that allows them to attack all attackable objects a chosen opponent controls.
   1. Attackable objects include Siegeable domains.
2. Cleave attacks can’t be intercepted.
3. Attacks with cleave involve only one combat step; damage is done simultaneously to each defending unit and retaliation is selected for each defending unit during the retaliation step of that combat.
4. Defending allies for a combat step initiated by a Cleave attack are designated during attack declaration. Any units that enter the field under the defending player’s control will not be designated as defenders and will not be involved in combat as defenders.

{% hint style="info" %}
E.g. A player chosen for a Cleave attack activates and resolves Blanche, Sheltering Saint at the beginning of the retaliation step of combat. Blanche would not be considered a defending unit and would not be able to retaliate nor would be dealt damage during the damage step.

![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/blanche-sheltering-saint-ftc.jpg)![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/hurricane-sweep-sp1.jpg)
{% endhint %}

5. An attack with Cleave may be retaliated against by each defending unit.
6. Each damage calculation is done independently but damage resolution happens simultaneously.
7. Damage done as a result of an attack with Cleave only causes the loss of one durability counter on a weapon if that weapon is used with the attack.
8. Multiple instances of Cleave are redundant.



#### Critical N <a href="#critical" id="critical"></a>

1. Critical N is a static ability which means “If this would deal combat damage, instead double that damage unless an opponent discards N cards.”
2. Any opponent may discard N cards even if a unit they control is not receiving the damage.
3. Multiple instances of critical stack from a single source additively. E.g. An ally with both Critical 2 and Critical 3 will require opponents to, in any combination, discard 2 and 3 cards, otherwise the damage is doubled. Damage will only be doubled once, regardless of how many instances of Critical are involved.



#### Command

1. Command is a static ability on Command Attacks that invokes an additional cost and modifies the attack card so that it is performed through an ally rather than a champion.
   1. Commands have an alternative additional cost of resting an ally (it must be awake). The command ability may include a subtype that specifies which ally type must be rested. This replaces the additional cost of resting a champion to activate an attack card.
   2. You do not rest your champion to activate attacks with the command ability.
2. After an attack with command resolves, a combat phase will begin with the rested ally as the attacker rather than a chosen champion. The attack card added to the rested ally's intent for the combat phase.
   1. Commands that resolve without a valid target will not create a combat phase; the rested ally will not enter combat.
   2. The ally must still obey its controller to attack. This means if a condition such as Pride is not met, the attack will fail to begin, no combat phase will start, and the attack card will enter the graveyard. The ally would remain rested.
3. If an attack card with the command ability were to be placed into an intent, the attacker's object typing will be checked against any specified subtypes for the ability as a state-based action. If the specified subtype for the command ability is not met and the command in the intent is not a legal attack for the attacker, the attack card will be placed in the graveyard as a result of state-based effects.

{% hint style="success" %}
Damage will be dealt by a unit according to its damage stat and the damage stats of any cards in its intent.
{% endhint %}



#### Divine Relic

1. Divine Relic is a static ability which means “You can only have one card with this keyword in your material deck.”



#### Efficiency

1. Efficiency is a cost-modifying static ability for a card or ability which means “This card costs LV less to activate” ([LV](game-terms.md#lv) refers to your champion’s level).
2. Efficiency functions only while a card is being placed onto the Effects Stack.



#### Element Bonus

1. Element Bonus is a restriction ability that defines a bonus effect or replacement effect for a card that is enabled if and only if the player’s champion’s element(s) matches the element of the card or object.
2. Element Bonus functions in all zones.

ability

#### Empower N

1. Empower is a static ability which means "The next Spell card you activate this turn activates and resolves as if your champion got +N level(s)."
   1. Empower must take a value greater than 0 to happen; a spell will not be empowered if an effect gave Empower 0.
2. Empower is granted to the player that controls the card or effect granting Empower. It is applied as a continuous effect that is used and applied as soon as the Empowered player activates their next Spell card.
   1. Empower is not applied as an effect to the activated card, but the card can check if it is being empowered by the player.
3. Multiple instances of empower stack additively.



#### Ephemerate

1. Ephemerate is a static ability which means "You may activate this card from the graveyard by paying its ephemerate cost."
   1. The ephemerate cost is separated by an "—". Any modifiers to this cost or ability are listed after this cost.
   2. As ephemerate coutns as an alternative activation that is not given any special permissions or timing windows (unlike Starcalling), the activation must follow the default speed of the card.
2. Allies played using the this ability become Ephemeral as they enter the field.
   1. Ephemeral is a property which specifies that ephemeral objects are banished whenever they would leave the field.
   2. Ephemeral as a propety applied to objects will not be applied to the card that object represents. If the card would move zones, the card does not retain "ephemeral" any subsequent objects represented by that card (unless otherwise specified) would not be ephemeral.

{% hint style="success" %}
If an effect would banish an ephemeral card, that card will still be able to track that object as the destination has not changed. E.g., any form of temporary banishing and then returning to the field, such as suppressing, would allow the card to return to the field. If it is returned this way, it is considered a new object and will not "remember" that it was ephemeral; the new object is not ephemeral.
{% endhint %}



#### Floating Memory

1. Floating Memory is a static ability which means “While paying for a memory cost, you may banish this card from your graveyard to pay for 1 of that cost.”
2. When paying a memory cost, the part of the cost paid with floating memory must be declared before determining the number of cards that are randomly banished as part of paying for memory costs.
3. Floating memory is redundant.



#### Fast Activation

1. Fast Activation is a static ability which means “You may activate this card at fast speed.”
2. Fast Activation is redundant.



#### Foster

1. Foster is a triggered ability which means “At the beginning of your recollection phase, if this ally hasn't been dealt damage since the end of your previous turn, it becomes fostered.”
2. Any unit may become fostered, but units can’t make themselves fostered without the Foster keyword.
3. Foster is redundant.



#### Hindered

1. Hindered is a static ability which means, "This object enters the field rested."
2. Hindered is redundant.



#### Imbue N

1. Imbue is an static ability which means, “You may reserve all cards revealed as you activate this card. If at least N of them are \<element matching the card>, this card becomes imbued."
2. Fulfilling the condition of the imbue ability will cause the card that resolves or the object the card would become to be imbued.
3. Cards that are set in the memory zone revealed are not revealed from the memory zone. They are just placed face-up in the memory zone. This means it will not trigger off of cards being revealed from memory.
4. Cards revealed for Imbue will be turned face down after the card is successfully activated and placed on the effects stack.
5. If a card has multiple instances of Imbue, only the smallest value of N needs to be met for a card to be imbued.



#### Immortality

1. Immortality is a static ability which means “This object can’t be sent from the field to the graveyard.”
   1. Immortal objects do not die; they do not go to the graveyard as a result of having 0 or less life.
   2. Immortal objects can’t be destroyed (including via sacrifice).
2. If a player controls multiple Immortal objects that are unique and have the same name, a player will still be forced to put one of those objects into their graveyard as a state-based effect as a result of breaking the Unique rule.
   1. Rule 2 takes precedence over Rule 1 and allows Rule 1 to be ignored in these cases.
   2. This counts as dying or being destroyed.
3. Immortality is redundant.



#### Inherited Effect

1. An Inherited Effect is a static ability applied to champion cards which means “Your champion has this ability as long as this card is part of its lineage.”
2. Inherited Effect only functions while the card with the ability is in a Lineage.



#### Intercept

1. Intercept is a triggered ability which means “Whenever your champion is attacked while this ally is awake, you may redirect that attack to this ally.”
   1. The ally must still be a valid target for the attack to be redirected.
2. If an ally with intercept does not obey a player, the resolution of the intercept ability will fail and that ally will not be able to intercept. The trigger still occurs and Opportunity is presented if a player has any effects that might cause that ally to obey the controlling player.
   1. Intercept will trigger, but will not allow the player to make that ally intercept if that ally does not obey that player.
3. Intercept is redundant.



#### Kindle N

1. Kindle is a static ability which means "you may banish up to N fire element cards fromyour graveyard as you activate this card. Each one pays for 1 reserve of this card's cost."
2. Kindle does not modify a card's cost characteristics regardless of how its payment is opted for.



#### Level Restriction

1. Level Restrictions (formatted as bubbles with Level N+) are restriction abilities that check if a player’s champion is at least level N.
2. Level Restrictions function in all zones.



#### Lineage (Keyword)

1. Lineage is a static restriction ability for leveling up a champion which means “\[CARDNAME] must be leveled from a previous level ‘X’ champion” where X is the character name of the previous champion.

{% hint style="info" %}
E.g., Lorraine, Wandering Warrior is a Lorraine champion and would be a valid condition for leveling into Lorraine, Blademaster.

![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/lorraine-wandering-warrior-doa-alter.jpg)![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/lorraine-blademaster-doa-alter.jpg)
{% endhint %}



#### Lineage Release

1. Lineage Release is an activated ability that says “activate this ability by banishing this card from your champion’s inner lineage.”
2. Lineage Release abilities on one card do not allow a player to banish another card with a Lineage Release ability for the cost of the written ability; only the effect of the ability of the card banished will be put onto the Effects Stack awaiting resolution.
3. These abilities can only be activated if the card with Lineage Release is in the Inner Lineage (i.e., it is not the player’s champion).



#### Link

1. Link is a static ability of objects that can confer type changes, value or stat modifications, or grant abilities to the Linked object.
2. Objects that enter the field after resolution from the effects stack that specify a Link ability become linked to a targeted object, typically preceding the Link word.
   1. If an object with a Link ability were to enter the field from a zone other than the effects stack, the linked object is just chosen as the object enters the field. It will not target anything.
   2. If the activation or materialization of the card with the Link ability has no legal targets, it will fizzle. If the object with the Link ability enters the field from a zone other than the effects stack and has no legal choices to Link to, it will be sacrificed (See points 6 and 7).

{% hint style="info" %}
E.g., Champion Link, Ally Link. The target object of the Link is the Linked object (and can be described as Linked ally, Linked champion, etc.).
{% endhint %}

3. Cards with Link abilities must specify the Link target when they are put onto the Effects Stack. If that object is no longer legal, it will fizzle.
4. A Link ability is broken when either the object with the Link ability or the Linked object leaves the field. The Link is also broken if it becomes illegal at any time, such as through type-changing or type-setting.
5. If the Link is destroyed as a result of the Linked object leaving the field in any way, the object with the Link ability is sacrificed as a state-based action (players must sacrifice it before any Opportunity is passed and any further player actions are taken).
6. An object can be under the effect of any number of Link abilities.
7. A Link only exists when at least one of the Linked objects has a legal Link.



#### Memory N+

1. Memory N+ is a restriction ability that defines a bonus effect or replacement effect for a card that is enabled if and only if the player has N or more cards in their memory zone.



#### On Attack

1. On Attack is a triggered ability condition.
2. On units, On Attack means “When this unit attacks.”
3. On cards in the intent and weapons, On Attack means "when this is used in an attack."



#### Omnishroud

1. Omnishroud is a static ability of objects which means “This can’t be targeted by activations, materializations, or triggered abilities.”
   1. Activations includes card and ability activations.
2. If an object receives Omnishroud while being targeted by an activation, materialization, or triggered ability, that target would be considered illegal.
   1. If that target was the only specified necessary target for the spell, the spell will fizzle.
3. Omnishroud is redundant.
   1. Spellshroud may still be applied to objects with Omnishroud, but will defer targeting permissions to those set by Omnishroud since Omnishroud is more restrictive.

#### On Banish

1. On Banish is a triggered ability condition that means "When this is banished."
2. The unit is only considered to be banished if it goes directly to banishment when it dies; On Banish will not trigger if the unit is sent anywhere else as a result of a replacement effect.
3. On Banish triggers from the field and considers the source of the ability as the object that was banished, not the card itself that is placed in banishment.



#### On Charge N

1. On Charge is a triggered ability condition which means "the first time this object has N charge counters on it."
   1. The triggered ability will only trigger once, the first time it has N charge counters. It will not trigger again regardless of whether the charge counters are removed and it regains charge counters in some way.
2. At the beginning of a player's recollection step as a turn-based action (TBA), that player puts a charge counter on each of their objects with an untriggered On Charge ability.



#### On Death

1. On Death is a triggered ability condition that means “When this dies.”
   1. Only units can die. Non-units are still considered destroyed, but are not considered to have died.
2. The unit is only considered to have died if it goes directly to the graveyard when it dies; On Death will not trigger if the unit is sent to banishment as a replacement for being sent to the graveyard.
3. On Death triggers from the field and considers the source of the ability as the object that died, not the card itself that is placed in the graveyard.



#### On Enter

1. On Enter is a triggered ability condition of objects that means “When this enters the field.”
2. For champions, On Enter will consider the card entering the Lineage as the topmost champion card as if that card had entered the field (it is not a new object).



#### On Foster

1. On Foster is a triggered ability condition which means “Whenever this unit becomes fostered.”



#### On Hit

1. On Hit is a triggered ability condition.
2. On units, On Hit means “When this deals combat damage to an attackable object.”
   1. On Hit will trigger off of hitting a Siegeable domain with damage dealt in the form of loss of durability counters from that domain.
3. On intents and weapons, On Hit means “When an attack or retaliation using this deals combat damage to an attackable object”

{% hint style="info" %}
E.g. On Hit triggers on any unit being dealt combat damage, typically through attacks or retaliations. On Ally Hit triggers only when the combat damage is dealt to an ally unit. On Champion Hit triggers only when the combat damage is dealt to a champion unit.
{% endhint %}

4. If an On Hit ability specifies an effect that specifies “that opponent” or\
   “that player,” this language will specify the opponent or player controlling the object that was hit.



#### On Kill

1. On Kill is a triggered ability condition when attacked units are killed by an attack.
   1. Units are killed as a result of having 0 or less life as a state-based effect.
   2. Siegeable domains are destroyed as a result of having 0 or less durability as a state-based effect but will not trigger On Kill as they are not considered units.
2. On units, On Kill means “When a unit is killed as a result of being dealt combat damage by this.”
3. On intents and weapons, On Kill means “When a unit is killed as a result of being dealt combat damage in an attack using this.”

{% hint style="success" %}
See [killed](game-terms.md#dies): "A unit is only considered to... have been killed if and only if it enters the graveyard directly from play." This means that On Kill will only trigger if the unit went to the graveyard directly due to the combat damage dealt, and not through any secondary effects, such as On Hit abilities that then would kill the unit.
{% endhint %}



#### On Leave

1. On Leave is a triggered ability condition that means “When this leaves the field.”
2. On Leave triggers from the field and considers the source of the ability as the object that left play, not the card itself that is moved to another zone.



#### Prepare N <a href="#prepare" id="prepare"></a>

1. Prepare is an optional cost-modifying static ability of some cards which means, “As an additional cost to activate \[CARDNAME], you may remove N Preparation counters from your champion. If you do, \[CARDNAME] becomes prepared as it’s activated.”
2. If the Prepare cost was paid, the card becomes “prepared.”



#### Preserve/Preserved <a href="#preserve" id="preserve"></a>

1. Preserve on objects means, “When \[CARDNAME] is destroyed, put it into its owner’s material deck revealed and Preserved. You may return a Preserved card from your material deck to your hand instead of materializing when you would materialize.” Objects with Preserve will have a trigger when they are destroyed which will cause the object’s card to be sent from the graveyard to the material deck “Preserved.”
2. Preserve on non-objects means, “As \[CARDNAME] resolves and would be placed into the graveyard, instead put it into its owner’s material deck revealed and Preserved. You may return a Preserved card from your material deck to your hand instead of materializing when you would materialize.” Non-objects will have a replacement effect generated which will send the card to the material deck “Preserved” as it resolves rather than entering the graveyard.
   1. If a non-object card with Preserve would be banished instead of going to the graveyard as it resolves, the card’s controller may choose whether the card is Preserved or is banished.
3. Every card that is Preserved is added to the material deck face-up and remains face-up until it moves to the hand, memory, or other zone considered as private information.
4.  “Preserved” is a card property that allows the card to be added back to a player’s hand when they would materialize instead of materializing a card.

    1. This will not count as a materialization.
    2. Preserved cards must stay revealed for as long as they remain Preserved.
    3. Returning a Preserved card to replace a materialization only requires that a player is given an opportunity to materialize, regardless of whether or not the player has a card they are able to materialize.
       1. _"No Double Dipping"_: If a permission would be given to "play" a card, only the materialization choice would be able to be replaced and the player can't also activate a card while replacing the option to materialize.



#### Pride N <a href="#pride" id="pride"></a>

1. Pride is a static ability which means “This ally won’t obey you unless your champion is level N or higher.” (Refer to [Obedience](game-terms.md#obedience).)
2. If an object has multiple instances of pride, only the highest value is taken into consideration for obedience.



#### Ranged N <a href="#ranged" id="ranged"></a>

1. Ranged N is a static ability for units which means “As long as this unit is distant, its attacks get +N power.”
2. Multiple instances of Ranged stack additively.



#### Renewable

1. Renewable is a static ability of Regalia which means “If this card would be banished from the field or an intent, put it into its owner’s material deck instead.”
2. Renewable will not function from any other zones, such as the object-specific zone of loaded cards (See [Object-Specific Zones](../game-mechanics/game-mechanics-game-zones/game-zones-object-specific-zones.md)).
3. Renewable is redundant.



#### Reservable

1. Reservable is a static ability of objects which means “while paying for a reserve cost, you may rest this object to pay for 1 of that cost.”
2. Reservable can pay for any costs that require a reserve cost, including activation costs, added or extra reserve costs, or taxed reserve costs.
3. Reservable is redundant.



#### Retort N

1. Retort is a static ability which means "As long as this ally is retaliating, it gets +N power."



#### Spellshroud

1. Spellshroud is a static ability which means “This object can't be targeted by spells,” where Spells are cards, effects, or sources that have or are granted the Spell subtype.
   1. Triggers generated by a Spell object are themselves of the Spell subtype and therefore cannot target objects with Spellshroud.
2. If an object receives Spellshroud while being targeted by a spell, that target would be considered illegal.
   1. If that target was the only specified necessary target for the spell, the spell will fizzle.
3. Spellshroud is redundant.



#### Starcalling

1. Starcalling is a static ability of cards which means “As you’re looking at this card while glimpsing, you may activate it by paying this cost. If you do, put all other cards you’re looking at on the bottom of your deck in any order.”
   1. Activating a card this way can ignore the default play speed.
2. Starcalling is an alternative cost for activating cards,
3. When a player activates a card using the Starcalling cost, that player will put all other cards seen while glimpsing at the bottom of the deck in any order; they may not choose to put any cards on the top of the deck.
4. Starcalling costs can still be modified by activation cost modifiers.
5. Starcalling only functions from the Main Deck and cards activated by paying for Starcalling costs are considered as activated from the Main Deck and no other zones.
6. Once a card is activated via Starcalling, it will be placed onto the effects stack but will not begin to resolve until any and all currently resolving effects are fully resolved.



#### Steadfast

1. Steadfast is a static ability which means “This ally can retaliate while rested and doesn’t rest to do so.”
2. Steadfast is redundant.



#### Stealth

1. Stealth is a static ability of units which means "This object can't be targeted by attacks unless permitted by True Sight."
2. Objects that were declared as retaliating against an attack before receiving stealth will still retaliate against their retaliation target and will deal damage accordingly during the combat phase.
3. If an object receives stealth while being the target of an attack, that target is considered illegal for the attack, and the attack is fizzled unless the attacking object has true sight. The defending object stops being a defending object and the attacking unit stops being an attacking object.
4. Stealth is redundant.



#### Taunt

1. Taunt is a static ability.
2. When declaring target(s) for an attack, a player must target awake units with Taunt over other attackable objects, if able.
   1. Attacks may be redirected or changed from the ally with taunt after initial attack declarations.
3. If multiple objects with Taunt are in play, the attacking player can choose which of those units to attack.
4. Taunt is redundant. An object with Taunt and Taunt does not have to be attacked with higher priority over an object with a single instance of Taunt.



#### True Sight

1. True Sight is a static ability.
   1. On units, True Sight means "This unit's attacks can target objects with stealth."
   2. On weapons, True Sight means "Attacks using this weapon can target objects with stealth."
2. True Sight is redundant.



#### Unblockable

1. Unblockable is a static ability which means "This unit's attacks can't be intercepted and ignore taunt."
2. Attack target(s) from an unblockable unit can still be changed (See [redirect](game-terms.md#redirect).)
3. Unblockable is redunant.



#### Vigor

1. Vigor is a triggered ability of units which means "This unit wakes up at the beginning of your end step."
2. Multiple instances of Vigor will create separate triggers during the end step.
