---
title: MapItem
---
//[Perry](../../../index.html)/[server.maps](../index.html)/[MapItem](index.html)



# MapItem



[jvm]\
class [MapItem](index.html)(**meso**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **item**: [Item](../../client.inventory/-item/index.html)?, **pos**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), **dropper**: [MapObject](../-map-object/index.html), **owner**: [Character](../../client/-character/index.html)?, **dropType**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), **playerDrop**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **questId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [AbstractMapObject](../-abstract-map-object/index.html)



## Functions


| Name | Summary |
|---|---|
| [getItemId](get-item-id.html) | [jvm]<br>fun [getItemId](get-item-id.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [sendDestroyData](send-destroy-data.html) | [jvm]<br>open override fun [sendDestroyData](send-destroy-data.html)(client: [Client](../../client/-client/index.html)) |
| [sendSpawnData](send-spawn-data.html) | [jvm]<br>open override fun [sendSpawnData](send-spawn-data.html)(client: [Client](../../client/-client/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [dropper](dropper.html) | [jvm]<br>val [dropper](dropper.html): [MapObject](../-map-object/index.html) |
| [dropType](drop-type.html) | [jvm]<br>val [dropType](drop-type.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [item](item.html) | [jvm]<br>val [item](item.html): [Item](../../client.inventory/-item/index.html)? = null |
| [itemLock](item-lock.html) | [jvm]<br>val [itemLock](item-lock.html): [ReentrantLock](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/locks/ReentrantLock.html) |
| [meso](meso.html) | [jvm]<br>val [meso](meso.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [objectId](index.html#-901661386%2FProperties%2F863300109) | [jvm]<br>open override var [objectId](index.html#-901661386%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [objectType](object-type.html) | [jvm]<br>open override val [objectType](object-type.html): [MapObjectType](../-map-object-type/index.html) |
| [ownerId](owner-id.html) | [jvm]<br>val [ownerId](owner-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? |
| [pickedUp](picked-up.html) | [jvm]<br>var [pickedUp](picked-up.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [playerDrop](player-drop.html) | [jvm]<br>val [playerDrop](player-drop.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [position](position.html) | [jvm]<br>open override var [position](position.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [questId](quest-id.html) | [jvm]<br>val [questId](quest-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

