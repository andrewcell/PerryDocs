---
title: Item
---
//[Perry](../../../index.html)/[client.inventory](../index.html)/[Item](index.html)



# Item



[jvm]\
open class [Item](index.html)(**itemId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **position**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), **quantity**: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), **petId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [Comparable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)<[Item](index.html)>



## Functions


| Name | Summary |
|---|---|
| [compareTo](compare-to.html) | [jvm]<br>open operator override fun [compareTo](compare-to.html)(other: [Item](index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [copy](copy.html) | [jvm]<br>open fun [copy](copy.html)(): [Item](index.html) |
| [getType](get-type.html) | [jvm]<br>open fun [getType](get-type.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |


## Properties


| Name | Summary |
|---|---|
| [cashId](cash-id.html) | [jvm]<br>var [cashId](cash-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [expiration](expiration.html) | [jvm]<br>var [expiration](expiration.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [flag](flag.html) | [jvm]<br>open var [flag](flag.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [giftFrom](gift-from.html) | [jvm]<br>var [giftFrom](gift-from.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [itemId](item-id.html) | [jvm]<br>val [itemId](item-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [log](log.html) | [jvm]<br>var [log](log.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)> |
| [owner](owner.html) | [jvm]<br>var [owner](owner.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pet](pet.html) | [jvm]<br>val [pet](pet.html): [Pet](../-pet/index.html)? |
| [petId](pet-id.html) | [jvm]<br>val [petId](pet-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [position](position.html) | [jvm]<br>var [position](position.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [quantity](quantity.html) | [jvm]<br>open var [quantity](quantity.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [sn](sn.html) | [jvm]<br>var [sn](sn.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |


## Inheritors


| Name |
|---|
| [Equip](../-equip/index.html) |
| [Pet](../-pet/index.html) |

