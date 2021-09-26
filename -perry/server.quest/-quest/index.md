---
title: Quest
---
//[Perry](../../../index.html)/[server.quest](../index.html)/[Quest](index.html)



# Quest



[jvm]\
class [Quest](index.html)(id: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html))



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [canComplete](can-complete.html) | [jvm]<br>fun [canComplete](can-complete.html)(c: [Character](../../client/-character/index.html), npcId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [canStart](can-start.html) | [jvm]<br>fun [canStart](can-start.html)(c: [Character](../../client/-character/index.html), npcId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [complete](complete.html) | [jvm]<br>fun [complete](complete.html)(c: [Character](../../client/-character/index.html), npc: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), selection: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null) |
| [forceComplete](force-complete.html) | [jvm]<br>fun [forceComplete](force-complete.html)(c: [Character](../../client/-character/index.html), npc: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forceStart](force-start.html) | [jvm]<br>fun [forceStart](force-start.html)(c: [Character](../../client/-character/index.html), npc: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forfeit](forfeit.html) | [jvm]<br>fun [forfeit](forfeit.html)(c: [Character](../../client/-character/index.html)) |
| [getItemAmountNeeded](get-item-amount-needed.html) | [jvm]<br>fun [getItemAmountNeeded](get-item-amount-needed.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMobAmountNeeded](get-mob-amount-needed.html) | [jvm]<br>fun [getMobAmountNeeded](get-mob-amount-needed.html)(mid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [reset](reset.html) | [jvm]<br>fun [reset](reset.html)(c: [Character](../../client/-character/index.html)) |
| [start](start.html) | [jvm]<br>fun [start](start.html)(c: [Character](../../client/-character/index.html), npc: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [autoPreComplete](auto-pre-complete.html) | [jvm]<br>var [autoPreComplete](auto-pre-complete.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [autoStart](auto-start.html) | [jvm]<br>var [autoStart](auto-start.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [completeActs](complete-acts.html) | [jvm]<br>val [completeActs](complete-acts.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[QuestAction](../-quest-action/index.html)&gt; |
| [completeReqs](complete-reqs.html) | [jvm]<br>val [completeReqs](complete-reqs.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[QuestRequirement](../-quest-requirement/index.html)&gt; |
| [id](id.html) | [jvm]<br>val [id](id.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [infoEx](info-ex.html) | [jvm]<br>var [infoEx](info-ex.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [infoNumber](info-number.html) | [jvm]<br>var [infoNumber](info-number.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [relevantMobs](relevant-mobs.html) | [jvm]<br>val [relevantMobs](relevant-mobs.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt; |
| [repeatable](repeatable.html) | [jvm]<br>var [repeatable](repeatable.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [startActs](start-acts.html) | [jvm]<br>val [startActs](start-acts.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[QuestAction](../-quest-action/index.html)&gt; |
| [startReqs](start-reqs.html) | [jvm]<br>val [startReqs](start-reqs.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[QuestRequirement](../-quest-requirement/index.html)&gt; |
| [timeLimit](time-limit.html) | [jvm]<br>var [timeLimit](time-limit.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [timeLimit2](time-limit2.html) | [jvm]<br>var [timeLimit2](time-limit2.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |

