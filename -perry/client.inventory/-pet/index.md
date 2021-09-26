---
title: Pet
---
//[Perry](../../../index.html)/[client.inventory](../index.html)/[Pet](index.html)



# Pet



[jvm]\
class [Pet](index.html)(**id**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **position**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), **uniqueId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [Item](../-item/index.html)



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
| [updatePosition](update-position.html) | [jvm]<br>fun [updatePosition](update-position.html)(movement: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[LifeMovementFragment](../../server.movement/-life-movement-fragment/index.html)>) |


## Properties


| Name | Summary |
|---|---|
| [cashId](index.html#-833050967%2FProperties%2F863300109) | [jvm]<br>var [cashId](index.html#-833050967%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [closeness](closeness.html) | [jvm]<br>var [closeness](closeness.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [expiration](index.html#-1544284728%2FProperties%2F863300109) | [jvm]<br>var [expiration](index.html#-1544284728%2FProperties%2F863300109): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [fh](fh.html) | [jvm]<br>var [fh](fh.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [flag](index.html#-1554961621%2FProperties%2F863300109) | [jvm]<br>open var [flag](index.html#-1554961621%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [fullness](fullness.html) | [jvm]<br>var [fullness](fullness.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 100 |
| [giftFrom](index.html#913820765%2FProperties%2F863300109) | [jvm]<br>var [giftFrom](index.html#913820765%2FProperties%2F863300109): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [itemId](index.html#-900416823%2FProperties%2F863300109) | [jvm]<br>val [itemId](index.html#-900416823%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [level](level.html) | [jvm]<br>var [level](level.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 1 |
| [log](index.html#-1594176417%2FProperties%2F863300109) | [jvm]<br>var [log](index.html#-1594176417%2FProperties%2F863300109): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)> |
| [name](name.html) | [jvm]<br>var [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [owner](index.html#-1227741616%2FProperties%2F863300109) | [jvm]<br>var [owner](index.html#-1227741616%2FProperties%2F863300109): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pet](index.html#1058896612%2FProperties%2F863300109) | [jvm]<br>val [pet](index.html#1058896612%2FProperties%2F863300109): [Pet](index.html)? |
| [petId](index.html#369527881%2FProperties%2F863300109) | [jvm]<br>val [petId](index.html#369527881%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [pos](pos.html) | [jvm]<br>var [pos](pos.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)? = null |
| [position](index.html#-747580658%2FProperties%2F863300109) | [jvm]<br>var [position](index.html#-747580658%2FProperties%2F863300109): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [quantity](index.html#1079458284%2FProperties%2F863300109) | [jvm]<br>open var [quantity](index.html#1079458284%2FProperties%2F863300109): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [sn](index.html#791348636%2FProperties%2F863300109) | [jvm]<br>var [sn](index.html#791348636%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [stance](stance.html) | [jvm]<br>var [stance](stance.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [summoned](summoned.html) | [jvm]<br>var [summoned](summoned.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [uniqueId](unique-id.html) | [jvm]<br>val [uniqueId](unique-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

