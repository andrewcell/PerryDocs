---
title: MonsterStatusEffect
---
//[Perry](../../../index.html)/[client.status](../index.html)/[MonsterStatusEffect](index.html)



# MonsterStatusEffect



[jvm]\
class [MonsterStatusEffect](index.html)(**stati**: [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[MonsterStatus](../-monster-status/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?>, **skill**: [Skill](../../client/-skill/index.html)?, **mobSkill**: [MobSkill](../../server.life/-mob-skill/index.html)?, **monsterSkill**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))



## Functions


| Name | Summary |
|---|---|
| [cancelDamageSchedule](cancel-damage-schedule.html) | [jvm]<br>fun [cancelDamageSchedule](cancel-damage-schedule.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? |
| [cancelTask](cancel-task.html) | [jvm]<br>fun [cancelTask](cancel-task.html)() |
| [removeActiveStatus](remove-active-status.html) | [jvm]<br>fun [removeActiveStatus](remove-active-status.html)(stat: [MonsterStatus](../-monster-status/index.html)) |
| [setValue](set-value.html) | [jvm]<br>fun [setValue](set-value.html)(status: [MonsterStatus](../-monster-status/index.html), newVal: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? |


## Properties


| Name | Summary |
|---|---|
| [cancelTask](cancel-task.html) | [jvm]<br>var [cancelTask](cancel-task.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? = null |
| [damageSchedule](damage-schedule.html) | [jvm]<br>var [damageSchedule](damage-schedule.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? = null |
| [mobSkill](mob-skill.html) | [jvm]<br>val [mobSkill](mob-skill.html): [MobSkill](../../server.life/-mob-skill/index.html)? |
| [monsterSkill](monster-skill.html) | [jvm]<br>val [monsterSkill](monster-skill.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [skill](skill.html) | [jvm]<br>val [skill](skill.html): [Skill](../../client/-skill/index.html)? |
| [stati](stati.html) | [jvm]<br>val [stati](stati.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[MonsterStatus](../-monster-status/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?> |

