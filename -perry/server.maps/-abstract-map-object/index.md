---
title: AbstractMapObject
---
//[Perry](../../../index.html)/[server.maps](../index.html)/[AbstractMapObject](index.html)



# AbstractMapObject



[jvm]\
abstract class [AbstractMapObject](index.html) : [MapObject](../-map-object/index.html)



## Functions


| Name | Summary |
|---|---|
| [sendDestroyData](../-map-object/send-destroy-data.html) | [jvm]<br>abstract fun [sendDestroyData](../-map-object/send-destroy-data.html)(client: [Client](../../client/-client/index.html)) |
| [sendSpawnData](../-map-object/send-spawn-data.html) | [jvm]<br>abstract fun [sendSpawnData](../-map-object/send-spawn-data.html)(client: [Client](../../client/-client/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [objectId](object-id.html) | [jvm]<br>open override var [objectId](object-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [objectType](object-type.html) | [jvm]<br>abstract override val [objectType](object-type.html): [MapObjectType](../-map-object-type/index.html) |
| [position](position.html) | [jvm]<br>open override var [position](position.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |


## Inheritors


| Name |
|---|
| [MiniGame](../../server/-mini-game/index.html) |
| [PlayerShop](../../server/-player-shop/index.html) |
| [AbstractAnimatedMapObject](../-abstract-animated-map-object/index.html) |
| [Door](../-door/index.html) |
| [HiredMerchant](../-hired-merchant/index.html) |
| [MapItem](../-map-item/index.html) |
| [Mist](../-mist/index.html) |
| [PlayerNPCs](../-player-n-p-cs/index.html) |
| [Reactor](../-reactor/index.html) |

