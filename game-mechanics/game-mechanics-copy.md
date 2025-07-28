# Game Mechanics - Copy

Some cards or abilities can become a copy of a card, object, or ability, or may generate an object that is a copy of a card, object, or ability. Copying can refer to the effect of copying an object or card activation. A copy can refer to the copied card, object, or ability.&#x20;

General Rules:

1. Anything copied will assume the properties and characteristics inherited as a result of the zone in which it was copied.
   1. A copied activation of a card or ability is still considered an activation. A copied triggered ability is still considered an ability. This is true for all types of interactable objects.
   2. A card copied from the hand will cause the copy to behave as if it were in the hand. The same is true for other zones.
   3. Only copies of cards on the field (i.e., the objects the cards represent) will become permanent.
   4. Copies of cards that are not on the field will only persist as long as the effect that created the copy persists. However, a copy of a card with a corresponding object type will cause a token of that object to be summoned as it resolves (the original card copy itself still ceases to exist).
      1. A copy of an intent will remain in the intent until the end of combat.

{% hint style="success" %}
E.g., For 1.a., a copied intent is also an intent, a copied object is copied into the field, a copied activation is copied into the effects stack, etc.
{% endhint %}

2. Copied card activations and copied objects are under the control of the player who generated the copy.
3. A copied ability has the same source as the original ability activation or trigger, and references by name will refer to the source of the original ability.
4. Copy effects that state a player may choose new targets or modes for the copied ability or card activation allow the player to choose new targets or modes.
   1. This will not allow the player to modify any choices made in activating the original copy.
5. Copying a card is not the same as generating a card. A copied card will cease to exist after the duration of the effect that created



#### Copying Objects

1. When an object is copied, the new copy has all characteristics of the base printing of the current face of that card without any modifiers such as counters, rested/awake statuses, or other continuous one-shot effects applied to the card.
   1. Some properties that affect the card (as opposed to just the object the card has become) can be copied, such as: Imbued.
2. Any choices or modes made while the original was on the field do not count as copiable information or characteristics for the new object. If any abilities ask that a player choose an effect, this choice is not impacted by nor will it impact the original object’s choice.

{% hint style="warning" %}
![](https://api.gatcg.com/cards/images/nia-mistveiled-scout-doa-alter.jpg)

E.g., If a copy was made of Nia, Mistveiled Scout, the copy’s controller may choose a different card name from what was named by the original Nia while the new object’s On Enter ability is resolving. The new Nia will not “remember” which card was chosen by the original.
{% endhint %}

3. Copies of any intent will also be copied into the intent zone. Those copies will cease to exist at the end of combat.
4. Any subsequent changes to the original copy will not cause any changes in characteristics to any of the copies of the original.
5. When an object is copied, the copied object is solely used to reference characteristics, regardless of whether or not the copied object is itself a copy.
6. Copying a transformable card will cause the copy to have only the characteristics of the face-up side. This copy will not be able to transform unless it has a valid corresponding side.

#### Static Copying

1. Some objects may enter the field as a copy of another object. If it does, the generated object will act as if it enters as the original card with any On Enter abilities being placed onto the Effects Stack, if able. Otherwise, it will copy all other characteristics as point 1 made above.
2. Entering as a copy is not a triggered ability like On Enter.

#### Copying Abilities, Card Activations, and Materializations

1. Copying a card or ability activation, materialization, or triggered ability will cause another instance of that ability or card to be placed onto the Effects Stack with any chosen modes, alternative costs, values of X, or other choices made during activation to be identical to the new copy.
2. Any choices made during resolution may be different between the copy and the original.
3. If there is any property or characteristic of cards or objects associated with the activation, materialization, or triggered ability, that information is also copied.&#x20;

{% hint style="info" %}
E.g., an Imbued action activation that is copied will produce an Imbued copy.
{% endhint %}

4. A copied activation of a card with a field-permanent object type (such as Ally or Item) will cause the copied activation to enter as a token copy of that object with any characteristics matching those of the printed values.
5. A copied activation of a card that does not have a corresponding permanent object type (such as actions) will cease to exist after it resolves, is negated, or fizzles.

