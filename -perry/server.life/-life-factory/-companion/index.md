---
title: Companion
---
//[Perry](../../../../index.html)/[server.life](../../index.html)/[LifeFactory](../index.html)/[Companion](index.html)



# Companion



[jvm]\
object [Companion](index.html)



## Types


| Name | Summary |
|---|---|
| [BanishInfo](-banish-info/index.html) | [jvm]<br>data class [BanishInfo](-banish-info/index.html)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **map**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **portal**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [LoseItem](-lose-item/index.html) | [jvm]<br>data class [LoseItem](-lose-item/index.html)(**id**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **chance**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), **x**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) |
| [SelfDestruction](-self-destruction/index.html) | [jvm]<br>data class [SelfDestruction](-self-destruction/index.html)(**action**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), **removeAfter**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **hp**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [getLife](get-life.html) | [jvm]<br>fun [getLife](get-life.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [AbstractLoadedLife](../../../server.maps/-abstract-loaded-life/index.html)? |
| [getMonster](get-monster.html) | [jvm]<br>fun [getMonster](get-monster.html)(mid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Monster](../../-monster/index.html)? |
| [getNpc](get-npc.html) | [jvm]<br>fun [getNpc](get-npc.html)(nid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Npc](../../-npc/index.html) |


## Properties


| Name | Summary |
|---|---|
| [data](data.html) | [jvm]<br>val [data](data.html): [DataProvider](../../../provider/-data-provider/index.html) |
| [monsterStats](monster-stats.html) | [jvm]<br>val [monsterStats](monster-stats.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [MonsterStats](../../-monster-stats/index.html)> |

