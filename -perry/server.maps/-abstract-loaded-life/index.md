---
title: AbstractLoadedLife
---
//[Perry](../../../index.html)/[server.maps](../index.html)/[AbstractLoadedLife](index.html)



# AbstractLoadedLife



[jvm]\
abstract class [AbstractLoadedLife](index.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [AbstractAnimatedMapObject](../-abstract-animated-map-object/index.html)



## Constructors


| | |
|---|---|
| [AbstractLoadedLife](-abstract-loaded-life.html) | [jvm]<br>fun [AbstractLoadedLife](-abstract-loaded-life.html)(life: [AbstractLoadedLife](index.html)) |


## Functions


| Name | Summary |
|---|---|
| [isFacingLeft](../-abstract-animated-map-object/is-facing-left.html) | [jvm]<br>open override fun [isFacingLeft](../-abstract-animated-map-object/is-facing-left.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [sendDestroyData](../-map-object/send-destroy-data.html) | [jvm]<br>abstract fun [sendDestroyData](../-map-object/send-destroy-data.html)(client: [Client](../../client/-client/index.html)) |
| [sendSpawnData](../-map-object/send-spawn-data.html) | [jvm]<br>abstract fun [sendSpawnData](../-map-object/send-spawn-data.html)(client: [Client](../../client/-client/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [cType](c-type.html) | [jvm]<br>var [cType](c-type.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [cy](cy.html) | [jvm]<br>var [cy](cy.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [f](f.html) | [jvm]<br>var [f](f.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [fh](fh.html) | [jvm]<br>var [fh](fh.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [hidden](hidden.html) | [jvm]<br>var [hidden](hidden.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [id](id.html) | [jvm]<br>val [id](id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [mTime](m-time.html) | [jvm]<br>var [mTime](m-time.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [objectId](../-abstract-map-object/object-id.html) | [jvm]<br>open override var [objectId](../-abstract-map-object/object-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [objectType](../-abstract-map-object/object-type.html) | [jvm]<br>abstract override val [objectType](../-abstract-map-object/object-type.html): [MapObjectType](../-map-object-type/index.html) |
| [position](../-abstract-map-object/position.html) | [jvm]<br>open override var [position](../-abstract-map-object/position.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [rx0](rx0.html) | [jvm]<br>var [rx0](rx0.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [rx1](rx1.html) | [jvm]<br>var [rx1](rx1.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [stance](../-abstract-animated-map-object/stance.html) | [jvm]<br>open override var [stance](../-abstract-animated-map-object/stance.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [startFh](start-fh.html) | [jvm]<br>var [startFh](start-fh.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |


## Inheritors


| Name |
|---|
| [Monster](../../server.life/-monster/index.html) |
| [Npc](../../server.life/-npc/index.html) |

