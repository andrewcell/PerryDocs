---
title: BuddyListEntry
---
//[Perry](../../../index.html)/[client](../index.html)/[BuddyListEntry](index.html)



# BuddyListEntry



[jvm]\
data class [BuddyListEntry](index.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), group: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), characterId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), channel: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), visible: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))



## Parameters


jvm

| | |
|---|---|
| name |  |
| characterId |  |
| channel | should be -1 if the buddy is offline |
| visible |  |



## Constructors


| | |
|---|---|
| [BuddyListEntry](-buddy-list-entry.html) | [jvm]<br>fun [BuddyListEntry](-buddy-list-entry.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), group: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), characterId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), channel: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), visible: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [isOnline](is-online.html) | [jvm]<br>fun [isOnline](is-online.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Properties


| Name | Summary |
|---|---|
| [channel](channel.html) | [jvm]<br>var [channel](channel.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [characterId](character-id.html) | [jvm]<br>val [characterId](character-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [group](group.html) | [jvm]<br>val [group](group.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [name](name.html) | [jvm]<br>val [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [visible](visible.html) | [jvm]<br>val [visible](visible.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

