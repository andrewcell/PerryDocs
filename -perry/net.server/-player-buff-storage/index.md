---
title: PlayerBuffStorage
---
//[Perry](../../../index.html)/[net.server](../index.html)/[PlayerBuffStorage](index.html)



# PlayerBuffStorage



[jvm]\
class [PlayerBuffStorage](index.html)



## Functions


| Name | Summary |
|---|---|
| [addBuffsToStorage](add-buffs-to-storage.html) | [jvm]<br>fun [addBuffsToStorage](add-buffs-to-storage.html)(cid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), toStore: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[PlayerBuffValueHolder](../-player-buff-value-holder/index.html)>) |
| [getBuffsFromStorage](get-buffs-from-storage.html) | [jvm]<br>fun [getBuffsFromStorage](get-buffs-from-storage.html)(cid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[PlayerBuffValueHolder](../-player-buff-value-holder/index.html)> |


## Properties


| Name | Summary |
|---|---|
| [buffs](buffs.html) | [jvm]<br>val [buffs](buffs.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[PlayerBuffValueHolder](../-player-buff-value-holder/index.html)>> |
| [id](id.html) | [jvm]<br>val [id](id.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [mutex](mutex.html) | [jvm]<br>val [mutex](mutex.html): [ReentrantLock](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/locks/ReentrantLock.html) |

