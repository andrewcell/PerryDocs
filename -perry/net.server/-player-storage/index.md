---
title: PlayerStorage
---
//[Perry](../../../index.html)/[net.server](../index.html)/[PlayerStorage](index.html)



# PlayerStorage



[jvm]\
class [PlayerStorage](index.html)



## Functions


| Name | Summary |
|---|---|
| [addPlayer](add-player.html) | [jvm]<br>fun [addPlayer](add-player.html)(chr: [Character](../../client/-character/index.html)) |
| [disconnectAll](disconnect-all.html) | [jvm]<br>fun [disconnectAll](disconnect-all.html)() |
| [getAllCharacters](get-all-characters.html) | [jvm]<br>fun [getAllCharacters](get-all-characters.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Character](../../client/-character/index.html)&gt; |
| [getCharacterById](get-character-by-id.html) | [jvm]<br>fun [getCharacterById](get-character-by-id.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Character](../../client/-character/index.html)? |
| [getCharacterByName](get-character-by-name.html) | [jvm]<br>fun [getCharacterByName](get-character-by-name.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Character](../../client/-character/index.html)? |
| [removePlayer](remove-player.html) | [jvm]<br>fun [removePlayer](remove-player.html)(chr: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Character](../../client/-character/index.html)? |
| [saveAll](save-all.html) | [jvm]<br>fun [saveAll](save-all.html)() |


## Properties


| Name | Summary |
|---|---|
| [locks](locks.html) | [jvm]<br>val [locks](locks.html): [ReentrantReadWriteLock](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/locks/ReentrantReadWriteLock.html) |
| [rLock](r-lock.html) | [jvm]<br>val [rLock](r-lock.html): [ReentrantReadWriteLock.ReadLock](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/locks/ReentrantReadWriteLock.ReadLock.html) |
| [storage](storage.html) | [jvm]<br>val [storage](storage.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Character](../../client/-character/index.html)&gt; |
| [wLock](w-lock.html) | [jvm]<br>val [wLock](w-lock.html): [ReentrantReadWriteLock.WriteLock](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/locks/ReentrantReadWriteLock.WriteLock.html) |

