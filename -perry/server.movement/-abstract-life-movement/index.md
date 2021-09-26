---
title: AbstractLifeMovement
---
//[Perry](../../../index.html)/[server.movement](../index.html)/[AbstractLifeMovement](index.html)



# AbstractLifeMovement



[jvm]\
abstract class [AbstractLifeMovement](index.html)(type: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), position: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), duration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), newState: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) : [LifeMovement](../-life-movement/index.html)



## Functions


| Name | Summary |
|---|---|
| [serialize](../-life-movement-fragment/serialize.html) | [jvm]<br>abstract fun [serialize](../-life-movement-fragment/serialize.html)(lew: [LittleEndianWriter](../../tools.data.output/-little-endian-writer/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [duration](duration.html) | [jvm]<br>open override val [duration](duration.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [newState](new-state.html) | [jvm]<br>open override val [newState](new-state.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [position](position.html) | [jvm]<br>open override val [position](position.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [type](type.html) | [jvm]<br>open override val [type](type.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |


## Inheritors


| Name |
|---|
| [AbsoluteLifeMovement](../-absolute-life-movement/index.html) |
| [ChairMovement](../-chair-movement/index.html) |
| [JumpDownMovement](../-jump-down-movement/index.html) |
| [RelativeLifeMovement](../-relative-life-movement/index.html) |

