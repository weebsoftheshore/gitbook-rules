# Game Mechanics - Objects and Targeting

#### Objects

1. Objects are defined as instanced representations of cards on the field, which include champions, allies, weapons, items, domains, phantasias, as well as any tokens.
2. Units are a subset of objects that only include allies and champions. These objects are interactable by effects that specify "target ally," "target champion," or "target unit" (for both). "Choose" may also be used instead of target, but will select a target as part of effects rather than as an activation requirement.
3. Innate stats tied to card characteristics (e.g., written Life and Power values, etc.) stay on objects even if they change to an object type that may not necessarily use or interact with that stat.

{% hint style="success" %}
![](https://api.gatcg.com/cards/images/fracturize-ftc.jpg)![](https://api.gatcg.com/cards/images/warriors-longsword-doa-alter.jpg)\
\
E.g., If a Warrior champion attacks with Warrior's Longsword and the sword were to have its type changed to a&#x20;
{% endhint %}



#### Non-Objects

1. Non-objects exist largely as cards in their respective zones, i.e., a card in the hand, graveyard, deck, memory, or banishment.  They are treated as cards rather than objects and can't exist as an object representation on the field. This includes any activations, triggered abilities, or materializations.
   1. Activations are either cards or abilities that have been activated and are in the Effects Stack.
      1. Activations are interactable by effects that specify a target or chosen activation.
   2. Materializations are cards that have been materialized and are in the Effects Stack.
      1. Materializations are interactable by effects that specify a target or chosen materialization.
   3. This also applies to cards in a champion's inner lineage (not the topmost champion card), intents, and [Loaded Cards](../glossary/game-terms.md#loaded); essentially, the rule extends to any card-specific zone.
      1. These may be targeted by specific wording, such as "target card in an inner lineage," "target intent," or "target loaded card," respectively (these examples are not exhaustive).



#### Target

1. A "target" is a selected choice for the direction of an effect or action; the target is what those act upon. Whenever a target is specified, it can filter for and specify any of the aforementioned objects or non-object card types.&#x20;
2. An effect, action, activation, attack, etc., can only choose or target cards and/or objects of the specified types. I.e., If an effect specifies a specific object type as a target, it can only target objects of that type.&#x20;
   1. If an effect specifies objects by exclusion, it can target any objects that are not excluded.
   2. If an effect specifies or targets one or more cards in a certain zone, it may only affect cards in that zone.

{% hint style="info" %}
E.g., “Target ally” can only target allies. “Target non-champion object” can target any object that is not a champion (allies, weapons, items, domains, etc.)

![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/incendiary-fractal-ftc.jpg)![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/excalibur-cleansing-light-doa-alter.jpg)
{% endhint %}



3. Tokens of a certain type (such as ally or regalia) follow the targeting conventions of those cards.

{% hint style="info" %}
E.g., A token ally can be targeted by any effect that can target an ally or a token.
{% endhint %}

4. Special cases with targeting involve effects that specify something is chosen rather than targeted. This usually occurs during the resolution of the effects in situations where targets can't be anticipated or specified during the activation process.&#x20;

{% hint style="info" %}
E.g., the card Creative Shock instructs the player to choose a unit and deal 2 damage to it if a Fire card is discarded during the resolution of the spell. This only has a chosen unit after the spell has resolved and can't be specified before as the card to be discarded is yet unknown.

![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/creative-shock-doa-alter.jpg)
{% endhint %}

5. When effects of cards or abilities use a card type or subtype descriptor and do not refer to a card, activation, materialization, or source, these effects refer to the object with the described type or subtype on the field.
