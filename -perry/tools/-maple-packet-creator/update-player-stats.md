---
title: updatePlayerStats
---
//[Perry](../../../index.html)/[tools](../index.html)/[MaplePacketCreator](index.html)/[updatePlayerStats](update-player-stats.html)



# updatePlayerStats



[jvm]\
open fun [updatePlayerStats](update-player-stats.html)(stats: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)&lt;[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[CharacterStat](../../client/-character-stat/index.html), [Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)&gt;&gt;): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;



Gets an update for specified stats.



#### Return



The stat update packet.



## Parameters


jvm

| | |
|---|---|
| stats | The stats to update. |





[jvm]\
open fun [updatePlayerStats](update-player-stats.html)(stats: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)&lt;[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[CharacterStat](../../client/-character-stat/index.html), [Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)&gt;&gt;, itemReaction: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;



Gets an update for specified stats.



#### Return



The stat update packet.



## Parameters


jvm

| | |
|---|---|
| stats | The list of stats to update. |
| itemReaction | Result of an item reaction(?) |




