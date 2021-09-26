---
title: PartyAttackerEntry
---
//[Perry](../../../../index.html)/[server.life](../../index.html)/[Monster](../index.html)/[PartyAttackerEntry](index.html)



# PartyAttackerEntry



[jvm]\
inner class [PartyAttackerEntry](index.html)(**partyId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **channelServer**: [Channel](../../../net.server.channel/-channel/index.html)) : [Monster.AttackerEntry](../-attacker-entry/index.html)



## Functions


| Name | Summary |
|---|---|
| [addDamage](add-damage.html) | [jvm]<br>open override fun [addDamage](add-damage.html)(from: [Character](../../../client/-character/index.html), damage: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), updateAttackTime: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [contains](contains.html) | [jvm]<br>open override fun [contains](contains.html)(chr: [Character](../../../client/-character/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getAttackers](get-attackers.html) | [jvm]<br>open override fun [getAttackers](get-attackers.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Monster.AttackingCharacter](../-attacking-character/index.html)> |
| [getDamage](get-damage.html) | [jvm]<br>open override fun [getDamage](get-damage.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [killedMob](killed-mob.html) | [jvm]<br>open override fun [killedMob](killed-mob.html)(map: [GameMap](../../../server.maps/-game-map/index.html), baseExp: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mostDamage: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [resolveAttackers](resolve-attackers.html) | [jvm]<br>fun [resolveAttackers](resolve-attackers.html)(): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Character](../../../client/-character/index.html), [Monster.Companion.OnePartyAttacker](../-companion/-one-party-attacker/index.html)> |


## Properties


| Name | Summary |
|---|---|
| [attackers](attackers.html) | [jvm]<br>val [attackers](attackers.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Monster.Companion.OnePartyAttacker](../-companion/-one-party-attacker/index.html)> |
| [channelServer](channel-server.html) | [jvm]<br>val [channelServer](channel-server.html): [Channel](../../../net.server.channel/-channel/index.html) |
| [partyId](party-id.html) | [jvm]<br>val [partyId](party-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [totDamage](tot-damage.html) | [jvm]<br>var [totDamage](tot-damage.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |

