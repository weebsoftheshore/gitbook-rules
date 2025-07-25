# Game Mechanics - Counters

Counters are a special attribute of an object that holds both a type and numeric value.&#x20;

Depending on the type, counters will have various effects or enable certain abilities.

Counters can be tracked by using tokens, dice, or an agreed method by players in a game to denote the number and type of each counter on an object.

The quantity of a type of counter can be positively modified by gaining and negatively modified by spending to pay for a cost, or by loss/removal as a result of an effect.

Counters persist on an object or card in a zone as long as that card or object does not change zones. Cards being moved to another zone will cause its counters to be lost.

Counters can be subdivided into generic or special counters. Special counters have specific rules associated with the counter itself whereas generic counters do not grant or have inherent abilities/effects associated with them. Counters are considered generic if they are not listed below:

#### Buff

1. Buff counters statically modify an object’s power and life stats by +1 to each of those stats for every buff counter on that object.
2. If the object does not have a power or life stat, that stat will not be generated due to a buff counter being placed on that object.
3. Modifications from buff counters will be applied before any other changes to the base power and life stats of an ally.&#x20;
4. If buff counters are placed on an object with debuff counters, each buff counter will remove itself and a corresponding debuff counter.&#x20;

#### Damage

1. Damage counters are permanent counters on champions that are placed whenever a champion is dealt any type of damage.
2. Damage counters will mark damage in whole numbers starting from 0.
3. Damage counters reaching or exceeding the life stat of a champion is a condition that causes that champion to die or become defeated and a player loses if all of their champions die or are defeated.
4. Damage counters are removed by effects that Recover.

#### Debuff

1. Debuff counters statically modify an object’s power and life stats by -1 to each of those stats for every debuff counter on that object.
2. If the object does not have a power or life stat, that stat will not be generated due to a debuff counter being placed on that object.
3. Modifications from debuff counters will be applied before any other changes to the base power and life stats of an ally.
4. If debuff counters are placed on an object with buff counters, each debuff counter will remove itself and a corresponding buff counter.&#x20;

#### Durability

1. Cards with a durability stat will enter the field with a number of durability counters equal to that stat.
2. Durability counters on an object can exceed the printed durability stat of an object.
3. Weapons and Siegeable objects will be destroyed by state-based effects if their durability reaches 0.
4. If the object does not have a durability stat, the stat will not be generated as a result of a durability counter being placed on that object.

#### Enlighten

1. Enlighten counters have the following ability: “Remove 3 enlighten counters from \[CARDNAME]: Draw a card."

#### Level

1. Level counters on champions give that champion +1 Level for each level counter on that champion.

#### Omen

1. Omen counters designate the card(s) in banishment on which they are placed as Omens.
2. Rules text on cards which refers to Omens refers to the set of cards that have at least one Omen counter placed on them in banishment.

#### Wither

1. At the beginning of a player's main phase, if they control one or more objects with a wither counter on them, for each of those objects, they sacrifice it unless they pay 1 reserve for each wither counter in it, then remove those counters.
2. The triggered ability is sourced from the game rather than the objects on which the wither-related trigger originates.
3. The reserve cost to be paid for each object must be paid in full. If it is not completely paid, that object is sacrificed.
4. All wither counters are removed at the same time during the resolution of the triggered ability.
5. There is only one main phase per turn; wither will not create another trigger after returning to the main phase after combat if any wither counters were placed in a combat phase.

