---
title: AnimatedMapObject
---
//[Perry](../../../index.html)/[server.maps](../index.html)/[AnimatedMapObject](index.html)



# AnimatedMapObject



[jvm]\
interface [AnimatedMapObject](index.html) : [MapObject](../-map-object/index.html)



## Functions


| Name | Summary |
|---|---|
| [isFacingLeft](is-facing-left.html) | [jvm]<br>abstract fun [isFacingLeft](is-facing-left.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [sendDestroyData](../-map-object/send-destroy-data.html) | [jvm]<br>abstract fun [sendDestroyData](../-map-object/send-destroy-data.html)(client: [Client](../../client/-client/index.html)) |
| [sendSpawnData](../-map-object/send-spawn-data.html) | [jvm]<br>abstract fun [sendSpawnData](../-map-object/send-spawn-data.html)(client: [Client](../../client/-client/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [objectId](../-map-object/object-id.html) | [jvm]<br>abstract var [objectId](../-map-object/object-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [objectType](../-map-object/object-type.html) | [jvm]<br>abstract val [objectType](../-map-object/object-type.html): [MapObjectType](../-map-object-type/index.html) |
| [position](../-map-object/position.html) | [jvm]<br>abstract var [position](../-map-object/position.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [stance](stance.html) | [jvm]<br>abstract var [stance](stance.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |


## Inheritors


| Name |
|---|
| [AbstractAnimatedMapObject](../-abstract-animated-map-object/index.html) |

