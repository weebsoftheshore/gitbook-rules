# Game Mechanics - Objects and Targeting

Objects are typically things on the field that are interactable which include champion objects, ally objects, weapon objects, item objects, and domain objects, as well as any summoned objects such as tokens on the field. Effects that specify a target \<object type> can interact with these objects.

1. Units are a sub-category of objects which only include allies and champions. These objects are interactable by effects that specify target or chosen ally or champion.
2. Stats (e.g. Life, Power, etc) stay on objects even if they change to an object type that may not necessarily use or interact with that stat.

Activations are either cards or abilities that have been activated and are in the Effects Stack. Activations are interactable by effects that specify a target or chosen activation.

Materializations are cards that have been materialized and are in the Effects Stack. Materializations are interactable by effects that specify a target or chosen materialization.

Intents are cards placed in the Intent Zone during combat. Intents are interactable by effects that specify a target or chosen intent.

Non-objects exist as cards in their respective zones, i.e., a card in the hand, graveyard, deck, memory, banishment, or card-specific zones are treated as cards rather than objects. This is applies to cards within a Lineage (not the topmost champion card), Intents, and Loaded Cards.

A target can specify any of the aforementioned object or card types and an effect can only choose or target cards and/or object of the specified types. If an effect specifies a specific object type as a target, it can only target that object.&#x20;

1. If an effect specifies objects by exclusion, it can target any objects that are not excluded.

{% hint style="info" %}
E.g., “Target ally” can only target allies. “Target non-champion object” can target any object that is not a champion (allies, weapons, items, domains, etc.)

![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/incendiary-fractal-ftc.jpg)![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/excalibur-cleansing-light-doa-alter.jpg)
{% endhint %}

2. If an effect specifies or targets one or more cards in a certain zone, it may only affect cards in that zone.
3. Tokens of a certain type (such as ally or regalia) follow the targeting conventions of those cards.

{% hint style="info" %}
E.g. A token ally can be targeted by any effect that can target an ally or a token.
{% endhint %}

Special cases with targeting involve an effect specifying that something is chosen rather than targeted. This usually occurs during the resolution of the effects in situations where targets can't be anticipated or specified during the activation process.&#x20;

{% hint style="info" %}
E.g., the card Creative Shock instructs the player to choose a unit and deal 2 damage to it if a Fire card is discarded during the resolution of the spell. This only has a chosen unit after the spell has resolved and can't be specified before as the card to be discarded is yet unknown.

![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/creative-shock-doa-alter.jpg)
{% endhint %}

When effects of cards or abilities use a card type or subtype descriptor and do not refer to a card, activation, materialization, or source, these effects will mean the object with the described type or subtype on the field.
