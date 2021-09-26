---
title: SingleAttackerEntry
---
//[Perry](../../../../index.html)/[server.life](../../index.html)/[Monster](../index.html)/[SingleAttackerEntry](index.html)



# SingleAttackerEntry



[jvm]\
inner class [SingleAttackerEntry](index.html)(from: [Character](../../../client/-character/index.html), chServ: [Channel](../../../net.server.channel/-channel/index.html)) : [Monster.AttackerEntry](../-attacker-entry/index.html)



## Functions


| Name | Summary |
|---|---|
| [addDamage](add-damage.html) | [jvm]<br>open override fun [addDamage](add-damage.html)(from: [Character](../../../client/-character/index.html), damage: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), updateAttackTime: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [contains](contains.html) | [jvm]<br>open override fun [contains](contains.html)(chr: [Character](../../../client/-character/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getAttackers](get-attackers.html) | [jvm]<br>open override fun [getAttackers](get-attackers.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Monster.AttackingCharacter](../-attacking-character/index.html)&gt; |
| [getDamage](get-damage.html) | [jvm]<br>open override fun [getDamage](get-damage.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [killedMob](killed-mob.html) | [jvm]<br>open override fun [killedMob](killed-mob.html)(map: [GameMap](../../../server.maps/-game-map/index.html), baseExp: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mostDamage: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [chrId](chr-id.html) | [jvm]<br>val [chrId](chr-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [chServ](ch-serv.html) | [jvm]<br>val [chServ](ch-serv.html): [Channel](../../../net.server.channel/-channel/index.html) |
| [from](from.html) | [jvm]<br>val [from](from.html): [Character](../../../client/-character/index.html) |
| [lastAttackTime](last-attack-time.html) | [jvm]<br>var [lastAttackTime](last-attack-time.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0 |

