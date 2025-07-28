# Game Mechanics - Abilities

Abilities are characteristics of cards and objects that affect the game and either produce an instanced effect or a continuous effect for a specified duration (E.g. “until end of turn.”)

Abilities can be either Activated abilities, Triggered abilities, or Static abilities, and some abilities (or functional rules) can be bound by Restriction abilities.

1. Abilities intrinsic to the card are considered characteristics of the card and apply globally inside and outside of the game in all zones.&#x20;
   1. Keywords are an example of intrinsic card characteristics
   2. If the keyword is tied to a restriction, if an effect asks the game to check for the keyword, it will do so during resolution to determine the effect or action's legality. Failing the check would cause the game to act as if the checked characteristic is absent.

{% hint style="info" %}
Abilities tied to objects generally only function from the field; however, cards may specify zones in which that ability functions.
{% endhint %}

2. Abilities specifying a zone or zones in which they function may not function in any other zones.
3. Abilities specifying a zone or zones in which they do not function may function in other zones.
   1. Abilities of action cards generally only function in the Effects Stacks.
   2. Abilities of attack cards generally only function while they are in the intent.
   3. Abilities of non-action, non-attack cards generally only function while they exist on the field as objects.
4. Cards in the intent can activate and trigger their abilities as if they were objects, with the exception of any abilities that require resting, sacrificing, or performing any object-related ability as a cost. This means any abilities a card would have been able to trigger or activate when it would have been an object may be triggered or activated from the intent. Cards in the intent will also apply any static abilities as if they were objects.
   1. A card's static abilities, other than those that modify a card's characteristics, such as alternative play methods or abilities that grant special activation permissions. These abilities would reference the card as opposed to the object by name, as is by ability conventions.

Abilities can specify zones from where an effect may take place or from where that ability may be activated that are not their default functional zone (Effects Stack for action cards, the field for non-action card objects).

Multiple non-keyword abilities on a card or object are separated by paragraph breaks.

Some abilities can be granted temporarily or permanently to cards, objects, or players, by other effects or abilities.

Multiple instances of the same ability are taken into account only if that ability is not classified as redundant.

4. Redundant abilities and keywords of an object will only take effect once, regardless of the multiplicity of instances in which that ability or keyword is active.
5. Redundant abilities and keywords will only consider the first instance of that ability or keyword for counting purposes.

{% hint style="info" %}
E.g. If an ally has three instances of vigor, other cards and effects would see that ally as having only one ability. [Keywords](../../glossary/keywords-and-abilities.md) contains information on ability redundancy.
{% endhint %}

Abilities consider the source of the ability as the object or card that generated the ability and are controlled by the player who controlled that object or card that generated the ability, whether triggered or activated. If any ability refers to its source’s characteristics, the last known information regarding the source is used.

{% hint style="info" %}
E.g. If an ally with an On Death trigger has an effect based upon that ally’s power, the power considered will be that of the ally while it was on the field before it died.
{% endhint %}

6. An ability placed in the Effects Stack exists independently of its source and will not be negated or fizzled if its source ceases to exist or is itself negated. If the source of the ability has left the zone it was in or changed control, the last known information under its controller at that time is used.
7. All abilities in the Effects Stack are controlled by the player who controlled the source generating that ability.
8. Face-down cards or cards in any non-public zones will have all abilities, intrinsic or otherwise, concealed from each player. They are considered as just cards without any other characteristics until they are revealed or their characteristics are checked in some manner.



The following pages discuss these topics:

* [Activated Abilities](abilities-activated-abilities.md)
* [Triggered Abilities](abilities-triggered-abilities.md)
* [Static Abilities](abilities-static-abilities.md)
* [Restriction Abilities](abilities-restriction-abilities.md)
* [Ability Tracking](abilities-ability-tracking.md)
