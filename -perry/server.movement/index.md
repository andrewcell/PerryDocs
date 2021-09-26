---
title: server.movement
---
//[Perry](../../index.html)/[server.movement](index.html)



# Package server.movement



## Types


| Name | Summary |
|---|---|
| [AbsoluteLifeMovement](-absolute-life-movement/index.html) | [jvm]<br>open class [AbsoluteLifeMovement](-absolute-life-movement/index.html)(**unk**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **pixelsPerSecond**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), **type**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), **position**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), **duration**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **newState**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) : [AbstractLifeMovement](-abstract-life-movement/index.html) |
| [AbstractLifeMovement](-abstract-life-movement/index.html) | [jvm]<br>abstract class [AbstractLifeMovement](-abstract-life-movement/index.html)(**type**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), **position**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), **duration**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **newState**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) : [LifeMovement](-life-movement/index.html) |
| [ChairMovement](-chair-movement/index.html) | [jvm]<br>class [ChairMovement](-chair-movement/index.html)(**unk**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **type**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), **position**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), **duration**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **newState**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) : [AbstractLifeMovement](-abstract-life-movement/index.html) |
| [ChangeEquip](-change-equip/index.html) | [jvm]<br>class [ChangeEquip](-change-equip/index.html)(**wui**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [LifeMovementFragment](-life-movement-fragment/index.html) |
| [JumpDownMovement](-jump-down-movement/index.html) | [jvm]<br>class [JumpDownMovement](-jump-down-movement/index.html)(**pixelsPerSecond**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), **unk**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **fh**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **type**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), **position**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), **duration**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **newState**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) : [AbstractLifeMovement](-abstract-life-movement/index.html) |
| [LifeMovement](-life-movement/index.html) | [jvm]<br>interface [LifeMovement](-life-movement/index.html) : [LifeMovementFragment](-life-movement-fragment/index.html) |
| [LifeMovementFragment](-life-movement-fragment/index.html) | [jvm]<br>interface [LifeMovementFragment](-life-movement-fragment/index.html) |
| [RelativeLifeMovement](-relative-life-movement/index.html) | [jvm]<br>class [RelativeLifeMovement](-relative-life-movement/index.html)(**type**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), **position**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), **duration**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **newState**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) : [AbstractLifeMovement](-abstract-life-movement/index.html) |
| [TeleportMovement](-teleport-movement/index.html) | [jvm]<br>class [TeleportMovement](-teleport-movement/index.html)(**pixelsPerSecond**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), **type**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), **position**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), **newState**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) : [AbsoluteLifeMovement](-absolute-life-movement/index.html) |

