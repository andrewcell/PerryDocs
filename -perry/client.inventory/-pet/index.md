---
title: Pet
---
//[Perry](../../../index.html)/[client.inventory](../index.html)/[Pet](index.html)



# Pet



[jvm]\
class [Pet](index.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), position: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), uniqueId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [Item](../-item/index.html)



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [canConsume](can-consume.html) | [jvm]<br>fun [canConsume](can-consume.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [compareTo](../-item/compare-to.html) | [jvm]<br>open operator override fun [compareTo](../-item/compare-to.html)(other: [Item](../-item/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [copy](../-item/copy.html) | [jvm]<br>open fun [copy](../-item/copy.html)(): [Item](../-item/index.html) |
| [gainCloseness](gain-closeness.html) | [jvm]<br>fun [gainCloseness](gain-closeness.html)(x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [getType](../-item/get-type.html) | [jvm]<br>open fun [getType](../-item/get-type.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [saveToDatabase](save-to-database.html) | [jvm]<br>fun [saveToDatabase](save-to-database.html)() |
| [updatePosition](update-position.html) | [jvm]<br>fun [updatePosition](update-position.html)(movement: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[LifeMovementFragment](../../server.movement/-life-movement-fragment/index.html)&gt;) |


## Properties


| Name | Summary |
|---|---|
| [cashId](../-item/cash-id.html) | [jvm]<br>var [cashId](../-item/cash-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [closeness](closeness.html) | [jvm]<br>var [closeness](closeness.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [expiration](../-item/expiration.html) | [jvm]<br>var [expiration](../-item/expiration.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [fh](fh.html) | [jvm]<br>var [fh](fh.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [flag](../-item/flag.html) | [jvm]<br>open var [flag](../-item/flag.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [fullness](fullness.html) | [jvm]<br>var [fullness](fullness.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 100 |
| [giftFrom](../-item/gift-from.html) | [jvm]<br>var [giftFrom](../-item/gift-from.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [itemId](../-item/item-id.html) | [jvm]<br>val [itemId](../-item/item-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [level](level.html) | [jvm]<br>var [level](level.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 1 |
| [log](../-item/log.html) | [jvm]<br>var [log](../-item/log.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [name](name.html) | [jvm]<br>var [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [owner](../-item/owner.html) | [jvm]<br>var [owner](../-item/owner.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pet](../-item/pet.html) | [jvm]<br>val [pet](../-item/pet.html): [Pet](index.html)? |
| [petId](../-item/pet-id.html) | [jvm]<br>val [petId](../-item/pet-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [pos](pos.html) | [jvm]<br>var [pos](pos.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)? = null |
| [position](../-item/position.html) | [jvm]<br>var [position](../-item/position.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [quantity](../-item/quantity.html) | [jvm]<br>open var [quantity](../-item/quantity.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [sn](../-item/sn.html) | [jvm]<br>var [sn](../-item/sn.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [stance](stance.html) | [jvm]<br>var [stance](stance.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [summoned](summoned.html) | [jvm]<br>var [summoned](summoned.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [uniqueId](unique-id.html) | [jvm]<br>val [uniqueId](unique-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

