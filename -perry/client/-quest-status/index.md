---
title: QuestStatus
---
//[Perry](../../../index.html)/[client](../index.html)/[QuestStatus](index.html)



# QuestStatus



[jvm]\
class [QuestStatus](index.html)(**quest**: [Quest](../../server.quest/-quest/index.html), **status**: [QuestStatus.Status](-status/index.html), **npc**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))



## Types


| Name | Summary |
|---|---|
| [Status](-status/index.html) | [jvm]<br>enum [Status](-status/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[QuestStatus.Status](-status/index.html)> |


## Functions


| Name | Summary |
|---|---|
| [addMedalMap](add-medal-map.html) | [jvm]<br>fun [addMedalMap](add-medal-map.html)(mapId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getMedalProgressSize](get-medal-progress-size.html) | [jvm]<br>fun [getMedalProgressSize](get-medal-progress-size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getProgress](get-progress.html) | [jvm]<br>fun [getProgress](get-progress.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getQuestData](get-quest-data.html) | [jvm]<br>fun [getQuestData](get-quest-data.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [progress](progress.html) | [jvm]<br>fun [progress](progress.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setProgress](set-progress.html) | [jvm]<br>fun [setProgress](set-progress.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), pr: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [completionTime](completion-time.html) | [jvm]<br>var [completionTime](completion-time.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [forfeited](forfeited.html) | [jvm]<br>var [forfeited](forfeited.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [medalProgress](medal-progress.html) | [jvm]<br>val [medalProgress](medal-progress.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> |
| [npc](npc.html) | [jvm]<br>val [npc](npc.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [progresses](progresses.html) | [jvm]<br>val [progresses](progresses.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [AtomicString](../../tools/-atomic-string/index.html)> |
| [quest](quest.html) | [jvm]<br>val [quest](quest.html): [Quest](../../server.quest/-quest/index.html) |
| [status](status.html) | [jvm]<br>var [status](status.html): [QuestStatus.Status](-status/index.html) |

