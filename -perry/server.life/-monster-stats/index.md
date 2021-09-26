---
title: MonsterStats
---
//[Perry](../../../index.html)/[server.life](../index.html)/[MonsterStats](index.html)



# MonsterStats



[jvm]\
data class [MonsterStats](index.html)(hp: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mp: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), exp: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), level: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), removeAfter: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), boss: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), explosiveReward: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), ffaLoot: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), undead: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), buffToGive: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), cp: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), removeOnMiss: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), dropPeriod: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tagColor: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tagBgColor: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))



## Functions


| Name | Summary |
|---|---|
| [addLoseItem](add-lose-item.html) | [jvm]<br>fun [addLoseItem](add-lose-item.html)(li: [LifeFactory.Companion.LoseItem](../-life-factory/-companion/-lose-item/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [addSkills](add-skills.html) | [jvm]<br>fun [addSkills](add-skills.html)(skillList: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;&gt;) |
| [getAnimationTime](get-animation-time.html) | [jvm]<br>fun [getAnimationTime](get-animation-time.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getEffectiveness](get-effectiveness.html) | [jvm]<br>fun [getEffectiveness](get-effectiveness.html)(e: [Element](../-element/index.html)): [ElementalEffectiveness](../-elemental-effectiveness/index.html) |
| [hasSkill](has-skill.html) | [jvm]<br>fun [hasSkill](has-skill.html)(skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), level: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isMobile](is-mobile.html) | [jvm]<br>fun [isMobile](is-mobile.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeEffectiveness](remove-effectiveness.html) | [jvm]<br>fun [removeEffectiveness](remove-effectiveness.html)(e: [Element](../-element/index.html)): [ElementalEffectiveness](../-elemental-effectiveness/index.html)? |
| [setAnimationTime](set-animation-time.html) | [jvm]<br>fun [setAnimationTime](set-animation-time.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), delay: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? |
| [setEffectiveness](set-effectiveness.html) | [jvm]<br>fun [setEffectiveness](set-effectiveness.html)(e: [Element](../-element/index.html), ee: [ElementalEffectiveness](../-elemental-effectiveness/index.html)): [ElementalEffectiveness](../-elemental-effectiveness/index.html)? |


## Properties


| Name | Summary |
|---|---|
| [animationTimes](animation-times.html) | [jvm]<br>val [animationTimes](animation-times.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt; |
| [banishInfo](banish-info.html) | [jvm]<br>var [banishInfo](banish-info.html): [LifeFactory.Companion.BanishInfo](../-life-factory/-companion/-banish-info/index.html)? = null |
| [boss](boss.html) | [jvm]<br>var [boss](boss.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [buffToGive](buff-to-give.html) | [jvm]<br>val [buffToGive](buff-to-give.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [cool](cool.html) | [jvm]<br>var [cool](cool.html): [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;? = null |
| [cp](cp.html) | [jvm]<br>val [cp](cp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [dropPeriod](drop-period.html) | [jvm]<br>val [dropPeriod](drop-period.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [exp](exp.html) | [jvm]<br>val [exp](exp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [explosiveReward](explosive-reward.html) | [jvm]<br>val [explosiveReward](explosive-reward.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [ffaLoot](ffa-loot.html) | [jvm]<br>val [ffaLoot](ffa-loot.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [firstAttack](first-attack.html) | [jvm]<br>var [firstAttack](first-attack.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [hp](hp.html) | [jvm]<br>val [hp](hp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [level](level.html) | [jvm]<br>val [level](level.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [loseItem](lose-item.html) | [jvm]<br>val [loseItem](lose-item.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[LifeFactory.Companion.LoseItem](../-life-factory/-companion/-lose-item/index.html)&gt; |
| [mp](mp.html) | [jvm]<br>val [mp](mp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [name](name.html) | [jvm]<br>val [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [paDamage](pa-damage.html) | [jvm]<br>var [paDamage](pa-damage.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [removeAfter](remove-after.html) | [jvm]<br>val [removeAfter](remove-after.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [removeOnMiss](remove-on-miss.html) | [jvm]<br>val [removeOnMiss](remove-on-miss.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [resistance](resistance.html) | [jvm]<br>val [resistance](resistance.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Element](../-element/index.html), [ElementalEffectiveness](../-elemental-effectiveness/index.html)&gt; |
| [revives](revives.html) | [jvm]<br>var [revives](revives.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt; |
| [selfDestruction](self-destruction.html) | [jvm]<br>var [selfDestruction](self-destruction.html): [LifeFactory.Companion.SelfDestruction](../-life-factory/-companion/-self-destruction/index.html)? = null |
| [skills](skills.html) | [jvm]<br>var [skills](skills.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;&gt; |
| [tagBgColor](tag-bg-color.html) | [jvm]<br>val [tagBgColor](tag-bg-color.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [tagColor](tag-color.html) | [jvm]<br>val [tagColor](tag-color.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [undead](undead.html) | [jvm]<br>val [undead](undead.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

