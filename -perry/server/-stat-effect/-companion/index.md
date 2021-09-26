---
title: Companion
---
//[Perry](../../../../index.html)/[server](../../index.html)/[StatEffect](../index.html)/[Companion](index.html)



# Companion



[jvm]\
object [Companion](index.html)



## Types


| Name | Summary |
|---|---|
| [CancelEffectAction](-cancel-effect-action/index.html) | [jvm]<br>class [CancelEffectAction](-cancel-effect-action/index.html)(target: [WeakReference](https://docs.oracle.com/javase/8/docs/api/java/lang/ref/WeakReference.html)&lt;[Character](../../../client/-character/index.html)&gt;, effect: [StatEffect](../index.html), startTime: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) : [Runnable](https://docs.oracle.com/javase/8/docs/api/java/lang/Runnable.html) |


## Functions


| Name | Summary |
|---|---|
| [addBuffStatPairToListIfNotZero](add-buff-stat-pair-to-list-if-not-zero.html) | [jvm]<br>fun [addBuffStatPairToListIfNotZero](add-buff-stat-pair-to-list-if-not-zero.html)(list: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[BuffStat](../../../client/-buff-stat/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;&gt;, buffstat: [BuffStat](../../../client/-buff-stat/index.html), value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [loadFromData](load-from-data.html) | [jvm]<br>fun [loadFromData](load-from-data.html)(source: [Data](../../../provider/-data/index.html)?, sourceId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), skill: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), overTime: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [StatEffect](../index.html) |
| [loadItemEffectFromData](load-item-effect-from-data.html) | [jvm]<br>fun [loadItemEffectFromData](load-item-effect-from-data.html)(source: [Data](../../../provider/-data/index.html)?, itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [StatEffect](../index.html) |
| [loadSkillEffectFromData](load-skill-effect-from-data.html) | [jvm]<br>fun [loadSkillEffectFromData](load-skill-effect-from-data.html)(source: [Data](../../../provider/-data/index.html), skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), overtime: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [StatEffect](../index.html) |

