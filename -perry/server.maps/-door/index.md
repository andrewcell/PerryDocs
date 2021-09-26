---
title: Door
---
//[Perry](../../../index.html)/[server.maps](../index.html)/[Door](index.html)



# Door



[jvm]\
class [Door](index.html)(owner: [Character](../../client/-character/index.html), targetPosition: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)) : [AbstractMapObject](../-abstract-map-object/index.html)



## Functions


| Name | Summary |
|---|---|
| [sendDestroyData](send-destroy-data.html) | [jvm]<br>open override fun [sendDestroyData](send-destroy-data.html)(client: [Client](../../client/-client/index.html)) |
| [sendSpawnData](send-spawn-data.html) | [jvm]<br>open override fun [sendSpawnData](send-spawn-data.html)(client: [Client](../../client/-client/index.html)) |
| [warp](warp.html) | [jvm]<br>fun [warp](warp.html)(chr: [Character](../../client/-character/index.html), toTown: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [objectId](../-abstract-map-object/object-id.html) | [jvm]<br>open override var [objectId](../-abstract-map-object/object-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [objectType](object-type.html) | [jvm]<br>open override val [objectType](object-type.html): [MapObjectType](../-map-object-type/index.html) |
| [owner](owner.html) | [jvm]<br>val [owner](owner.html): [Character](../../client/-character/index.html) |
| [position](position.html) | [jvm]<br>open override var [position](position.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [target](target.html) | [jvm]<br>val [target](target.html): [GameMap](../-game-map/index.html) |
| [targetPosition](target-position.html) | [jvm]<br>val [targetPosition](target-position.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [town](town.html) | [jvm]<br>val [town](town.html): [GameMap](../-game-map/index.html) |
| [townPortal](town-portal.html) | [jvm]<br>val [townPortal](town-portal.html): [Portal](../../server/-portal/index.html) |

