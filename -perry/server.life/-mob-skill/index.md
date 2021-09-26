---
title: MobSkill
---
//[Perry](../../../index.html)/[server.life](../index.html)/[MobSkill](index.html)



# MobSkill



[jvm]\
class [MobSkill](index.html)(**skillId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **skillLevel**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **spawnEffect**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **hp**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **mpCon**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **x**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **y**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **duration**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **coolTime**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **prop**: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), **limit**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **lt**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), **rb**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))



## Functions


| Name | Summary |
|---|---|
| [addSummons](add-summons.html) | [jvm]<br>fun [addSummons](add-summons.html)(s: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> |
| [applyEffect](apply-effect.html) | [jvm]<br>fun [applyEffect](apply-effect.html)(chr: [Character](../../client/-character/index.html), monster: [Monster](../-monster/index.html), skill: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [makeChanceResult](make-chance-result.html) | [jvm]<br>fun [makeChanceResult](make-chance-result.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Properties


| Name | Summary |
|---|---|
| [coolTime](cool-time.html) | [jvm]<br>val [coolTime](cool-time.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [duration](duration.html) | [jvm]<br>val [duration](duration.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [hp](hp.html) | [jvm]<br>val [hp](hp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [limit](limit.html) | [jvm]<br>val [limit](limit.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [lt](lt.html) | [jvm]<br>val [lt](lt.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [mpCon](mp-con.html) | [jvm]<br>val [mpCon](mp-con.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [prop](prop.html) | [jvm]<br>val [prop](prop.html): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [rb](rb.html) | [jvm]<br>val [rb](rb.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [skillId](skill-id.html) | [jvm]<br>val [skillId](skill-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [skillLevel](skill-level.html) | [jvm]<br>val [skillLevel](skill-level.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [spawnEffect](spawn-effect.html) | [jvm]<br>val [spawnEffect](spawn-effect.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toSummon](to-summon.html) | [jvm]<br>val [toSummon](to-summon.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> |
| [x](x.html) | [jvm]<br>val [x](x.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [y](y.html) | [jvm]<br>val [y](y.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

