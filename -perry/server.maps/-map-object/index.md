---
title: MapObject
---
//[Perry](../../../index.html)/[server.maps](../index.html)/[MapObject](index.html)



# MapObject



[jvm]\
interface [MapObject](index.html)



## Functions


| Name | Summary |
|---|---|
| [sendDestroyData](send-destroy-data.html) | [jvm]<br>abstract fun [sendDestroyData](send-destroy-data.html)(client: [Client](../../client/-client/index.html)) |
| [sendSpawnData](send-spawn-data.html) | [jvm]<br>abstract fun [sendSpawnData](send-spawn-data.html)(client: [Client](../../client/-client/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [objectId](object-id.html) | [jvm]<br>abstract var [objectId](object-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [objectType](object-type.html) | [jvm]<br>abstract val [objectType](object-type.html): [MapObjectType](../-map-object-type/index.html) |
| [position](position.html) | [jvm]<br>abstract var [position](position.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |


## Inheritors


| Name |
|---|
| [AbstractMapObject](../-abstract-map-object/index.html) |
| [AnimatedMapObject](../-animated-map-object/index.html) |

