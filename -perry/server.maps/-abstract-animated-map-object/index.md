---
title: AbstractAnimatedMapObject
---
//[Perry](../../../index.html)/[server.maps](../index.html)/[AbstractAnimatedMapObject](index.html)



# AbstractAnimatedMapObject



[jvm]\
abstract class [AbstractAnimatedMapObject](index.html) : [AbstractMapObject](../-abstract-map-object/index.html), [AnimatedMapObject](../-animated-map-object/index.html)



## Functions


| Name | Summary |
|---|---|
| [isFacingLeft](is-facing-left.html) | [jvm]<br>open override fun [isFacingLeft](is-facing-left.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [sendDestroyData](../-map-object/send-destroy-data.html) | [jvm]<br>abstract fun [sendDestroyData](../-map-object/send-destroy-data.html)(client: [Client](../../client/-client/index.html)) |
| [sendSpawnData](../-map-object/send-spawn-data.html) | [jvm]<br>abstract fun [sendSpawnData](../-map-object/send-spawn-data.html)(client: [Client](../../client/-client/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [objectId](../-abstract-map-object/object-id.html) | [jvm]<br>open override var [objectId](../-abstract-map-object/object-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [objectType](../-abstract-map-object/object-type.html) | [jvm]<br>abstract override val [objectType](../-abstract-map-object/object-type.html): [MapObjectType](../-map-object-type/index.html) |
| [position](../-abstract-map-object/position.html) | [jvm]<br>open override var [position](../-abstract-map-object/position.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [stance](stance.html) | [jvm]<br>open override var [stance](stance.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |


## Inheritors


| Name |
|---|
| [Character](../../client/-character/index.html) |
| [AbstractLoadedLife](../-abstract-loaded-life/index.html) |
| [Summon](../-summon/index.html) |

