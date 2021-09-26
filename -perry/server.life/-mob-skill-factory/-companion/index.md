---
title: Companion
---
//[Perry](../../../../index.html)/[server.life](../../index.html)/[MobSkillFactory](../index.html)/[Companion](index.html)



# Companion



[jvm]\
object [Companion](index.html)



## Functions


| Name | Summary |
|---|---|
| [getMobSkill](get-mob-skill.html) | [jvm]<br>fun [getMobSkill](get-mob-skill.html)(skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), level: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [MobSkill](../../-mob-skill/index.html) |


## Properties


| Name | Summary |
|---|---|
| [dataLock](data-lock.html) | [jvm]<br>val [dataLock](data-lock.html): [ReentrantReadWriteLock](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/locks/ReentrantReadWriteLock.html) |
| [dataSource](data-source.html) | [jvm]<br>val [dataSource](data-source.html): [DataProvider](../../../provider/-data-provider/index.html) |
| [mobSkills](mob-skills.html) | [jvm]<br>val [mobSkills](mob-skills.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [MobSkill](../../-mob-skill/index.html)&gt; |
| [skillRoot](skill-root.html) | [jvm]<br>val [skillRoot](skill-root.html): [Data](../../../provider/-data/index.html)? |

