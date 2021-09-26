---
title: AttackerEntry
---
//[Perry](../../../../index.html)/[server.life](../../index.html)/[Monster](../index.html)/[AttackerEntry](index.html)



# AttackerEntry



[jvm]\
interface [AttackerEntry](index.html)



## Functions


| Name | Summary |
|---|---|
| [addDamage](add-damage.html) | [jvm]<br>abstract fun [addDamage](add-damage.html)(from: [Character](../../../client/-character/index.html), damage: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), updateAttackTime: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [contains](contains.html) | [jvm]<br>abstract fun [contains](contains.html)(chr: [Character](../../../client/-character/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getAttackers](get-attackers.html) | [jvm]<br>abstract fun [getAttackers](get-attackers.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Monster.AttackingCharacter](../-attacking-character/index.html)&gt; |
| [getDamage](get-damage.html) | [jvm]<br>abstract fun [getDamage](get-damage.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [killedMob](killed-mob.html) | [jvm]<br>abstract fun [killedMob](killed-mob.html)(map: [GameMap](../../../server.maps/-game-map/index.html), baseExp: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mostDamage: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |


## Inheritors


| Name |
|---|
| [Monster](../-single-attacker-entry/index.html) |
| [Monster](../-party-attacker-entry/index.html) |

