---
title: Reactor
---
//[Perry](../../../index.html)/[server.maps](../index.html)/[Reactor](index.html)



# Reactor



[jvm]\
class [Reactor](index.html)(**stats**: [ReactorStats](../-reactor-stats/index.html), **rid**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **delay**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **state**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), **name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **pos**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)) : [AbstractMapObject](../-abstract-map-object/index.html)



## Functions


| Name | Summary |
|---|---|
| [delayedHitReactor](delayed-hit-reactor.html) | [jvm]<br>fun [delayedHitReactor](delayed-hit-reactor.html)(c: [Client](../../client/-client/index.html), delay: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [getArea](get-area.html) | [jvm]<br>fun [getArea](get-area.html)(): [Rectangle](https://docs.oracle.com/javase/8/docs/api/java/awt/Rectangle.html) |
| [getReactItem](get-react-item.html) | [jvm]<br>fun [getReactItem](get-react-item.html)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>? |
| [getReactorType](get-reactor-type.html) | [jvm]<br>fun [getReactorType](get-reactor-type.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [hitReactor](hit-reactor.html) | [jvm]<br>fun [hitReactor](hit-reactor.html)(c: [Client](../../client/-client/index.html), charPos: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, stance: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0, skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0) |
| [makeSpawnData](make-spawn-data.html) | [jvm]<br>fun [makeSpawnData](make-spawn-data.html)(): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [sendDestroyData](send-destroy-data.html) | [jvm]<br>open override fun [sendDestroyData](send-destroy-data.html)(client: [Client](../../client/-client/index.html)) |
| [sendSpawnData](send-spawn-data.html) | [jvm]<br>open override fun [sendSpawnData](send-spawn-data.html)(client: [Client](../../client/-client/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [alive](alive.html) | [jvm]<br>var [alive](alive.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [delay](delay.html) | [jvm]<br>val [delay](delay.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [map](map.html) | [jvm]<br>var [map](map.html): [GameMap](../-game-map/index.html)? = null |
| [name](name.html) | [jvm]<br>val [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [objectId](index.html#-1914456695%2FProperties%2F863300109) | [jvm]<br>open override var [objectId](index.html#-1914456695%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [objectType](object-type.html) | [jvm]<br>open override val [objectType](object-type.html): [MapObjectType](../-map-object-type/index.html) |
| [position](position.html) | [jvm]<br>open override var [position](position.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [rid](rid.html) | [jvm]<br>val [rid](rid.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [state](state.html) | [jvm]<br>var [state](state.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [stats](stats.html) | [jvm]<br>val [stats](stats.html): [ReactorStats](../-reactor-stats/index.html) |
| [timerActive](timer-active.html) | [jvm]<br>var [timerActive](timer-active.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |

