# Types of Effects - Continuous Effects



#### General Rules:

1. Continuous effects can be generated due to resolved cards or abilities and can modify properties, stats, or other characteristics of cards, objects, activations, and materialization and can modify or set rules of the game or can affect players for defined or indefinite durations.
2. The duration of continuous effects is typically described by the rules text of the card that creates that effect. If no such duration is specified, the continuous effect lasts until the end of the game or until the object source of the ability leaves the field. The duration of continuous effects may be modified by conditions, typically using the wording “as long as,” which will update the "on-or-off" mode of that ability during [State-based](../../game-mechanics-miscellaneous-topics/state-based-checks-and-effects.md) checks.
3. There is no frame of time in which a player can act where cards, objects, activations, and materializations would not be under modifying continuous effects.



#### Instanced Effects

1. If the resolution of a card activation, materialization, or ability creates a continuous effect that modifies the [characteristics ](broken-reference)of objects or cards, that effect will only take into consideration the set of objects at the time that effect resolved. These are also known as "One-Shot effects." These effects typically use the words "get," "gain," or "become."&#x20;
2. The set of objects will not change for the duration of that effect; any new objects that enter play after these continuous effects begin will not be affected.&#x20;



#### Static Effects

1. If a continuous effect that modifies or sets rules in a game of Grand Archive is statically applied, the game will apply that effect to all cards within the described set at all times. These are known as "Static Effects" and can affect cards, objects, activations, and materializations that were not initially present when the object or card that created the effect first began. These effects can use language such as "get," "have,"  "are." See [here](../../../glossary/game-terms.md#have-gain-get-become-are).

{% hint style="info" %}
E.g., inspiring Call specifies that "allies you control **get** +1 power." Any allies that enter after the fact would not receive the +1 power as this effect is generated due to Inspiring Call's resolution. On the Other hand, Claude would give all Automaton allies you control the abilities of Taunt and "On Death: Glimpse 3" even if those allies entered play after Claude did, as Claude's effect is Static (i.e. those Automaton allies have a later [timestamp](./#timestamps).)

![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/inspiring-call-doa-alter.jpg)![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/claude-fated-visionary-alc.jpg)
{% endhint %}

{% hint style="danger" %}
E.g., Nullifying Lantern will set the element type of all cards in graveyards to Norm regardless of if those cards entered the graveyard after Nullifying Lantern entered play.

![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/nullifying-lantern-doa-alter.jpg)
{% endhint %}



#### Layers

Several continuous effects can be present during the game. In situations where an effect modifies the same properties of a card, object, or rule attributed to a player, those effects will take precedence based on the timestamp of the effect source. However, some effects can overlap, altering the same property, such as a card’s element or an ally’s power. Typically, these overlapping effects will be applied according to a "Timestamp" system (see below). Sometimes, these effects may need information about another continuous effect being applied on the same layer, creating a dependency.

1. Dependencies will override any timestamp-based determination of continuous effects. In these cases, there exists an order for how to apply these modifications, called "Layers". Layers of continuous effects are checked at the same time as state-based checks in the game.
2. Players receive no Opportunity to act as the game applies the effects through each layer. The order in which layers are applied is as follows:
   1. Layer A: Effects/rules setting base values and properties apply. This includes the setting of playing cost values. This includes setting of power, life, durability, levels, playing costs, and default play permissions (i.e., Fast vs Slow play speed).
   2. Layer B: Effects/rules that modify a card or object’s types (i.e. Supertype, Type, or Subtype) are applied.
   3. Layer C: Effects/rules modifying a card or object’s element are applied.
   4. Layer D: Effects/rules that add or subtract abilities are applied.
   5. Layer E: Effects/rules that increase or decrease power, life, durability, levels, playing costs, or modify play permissions (i.e., Fast vs Slow play speed).
   6. Specifically for power and life stats, several effects may modify these values in different ways and require a sub-layering: First, apply any changes from continuous effects that do not set these values. Then, apply any modifications from counters. Finally, if any effects may swap power and life, apply these last.



{% hint style="warning" %}
E.g., Nullifying Lantern and losing abilities — Nullifying Lantern says "Cards in graveyards are norm element.” If another effect causes Nullifying lantern to lose all abilities, Nullifying Lantern’s effect of changing element in the graveyard will still apply. This is because Nullifying Lantern’s effect operates on Layer C while loss of ability operates on Layer D; the effect applies in Layer C before the ability loss is applied in Layer D.

![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/nullifying-lantern-doa-alter.jpg)![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/fracturize-ftc.jpg)
{% endhint %}

#### Timestamps

Simultaneous continuous effects that modify the same property, characteristic, value, ability, etc. within the same layer are applied according to the “timestamp” established when the effect began. Independent continuous effects within a layer are applied sequentially in order of how recent the timestamp was established, oldest to newest (first to most recent). Effects creating dependencies will instead use a different method (below).

1. A timestamp can be tracked as a chronological marker where objects and their effects can be categorized as older or newer relative to when that effect began.
   1. For objects that have static abilities that create continuous effects, the timestamp for that effect is tied to when that object entered play.
   2. For cards and triggered or activated abilities that produce a continuous effect, the timestamp is tied to when that card or ability is resolved.
2. If the modified attribute happens in a mutually exclusive fashion, the newest static ability will override the older one; If they are not mutually exclusive, they will both be in effect according to the timestamping of the effects.
3.  For champions, the champion object and cards within the lineage will each follow specific timestamp rules.&#x20;

    1. The champion object, which is represented by the top-most card in the lineage, has its timestamp set as when the first champion card in that lineage entered the field (usually this is the Lv 0 Spirit Champion).
       1. Leveling up so that a new champion card represents the object is not considered a gain of abilities due to continuous effects and will not use Layers. That card's rules text is treated as the object's base rules text.
    2. Any cards that enter the lineage will have a timestamp for when that card entered the lineage. This is separate from the timestamp of the champion object and is used to track any abilities or continuous effects from the cards in the lineage.



#### Dependencies

Some continuous effects may modify characteristics or rules operating on the same layer where those effects are dependent upon the existence or modifications that arise from another effect.

1. A dependent effect is: applied in the same layer as another effect, modified in some way if another effect is applied first (either by a rules text change, objects to which they apply, or modifies the effect applied to those objects), and either both or neither set any characteristics (such as setting playing costs or any stats).
2. If the conditions to establish a dependency are fulfilled, then the timestamp system is disregarded and the dependent effect is applied only after any effects on which it depends are applied first.
   1. Timestamp order for dependent effects only applies for simultaneous dependent effects that are independent of each other in the same layer (i.e., those dependent effects do not depend on each other) or if those dependent effects form a loop with each other.
   2. The order in which effects can apply may change if a pending effect changes its dependency status, either becoming dependent or independent.



{% hint style="warning" %}
E.g., Mordred effect that gives attack cards in the graveyard Floating Memory depends on Caliburn of Silencing's ability. In this case, Caliburn's effect must be applied first since each ability is applied in Layer D for adding or subtracting abilities.

\
![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/mordred-flawless-blade-doa-alter.jpg)![](https://ga-index-public.s3.us-west-2.amazonaws.com/cards/caliburn-of-silencing-doap.jpg)
{% endhint %}



