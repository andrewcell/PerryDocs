---
title: Equip
---
//[Perry](../../../index.html)/[client.inventory](../index.html)/[Equip](index.html)



# Equip



[jvm]\
class [Equip](index.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), position: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), upgradeSlots: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) : [Item](../-item/index.html)



## Types


| Name | Summary |
|---|---|
| [ScrollResult](-scroll-result/index.html) | [jvm]<br>enum [ScrollResult](-scroll-result/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[Equip.ScrollResult](-scroll-result/index.html)&gt; |


## Functions


| Name | Summary |
|---|---|
| [compareTo](../-item/compare-to.html) | [jvm]<br>open operator override fun [compareTo](../-item/compare-to.html)(other: [Item](../-item/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [copy](copy.html) | [jvm]<br>open override fun [copy](copy.html)(): [Item](../-item/index.html) |
| [gainItemExp](gain-item-exp.html) | [jvm]<br>fun [gainItemExp](gain-item-exp.html)(c: [Client](../../client/-client/index.html), gain: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), timeless: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [gainLevel](gain-level.html) | [jvm]<br>fun [gainLevel](gain-level.html)(c: [Client](../../client/-client/index.html), timeless: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [getType](get-type.html) | [jvm]<br>open override fun [getType](get-type.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |


## Properties


| Name | Summary |
|---|---|
| [acc](acc.html) | [jvm]<br>var [acc](acc.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [avoid](avoid.html) | [jvm]<br>var [avoid](avoid.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [cashId](../-item/cash-id.html) | [jvm]<br>var [cashId](../-item/cash-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [dex](dex.html) | [jvm]<br>var [dex](dex.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [expiration](../-item/expiration.html) | [jvm]<br>var [expiration](../-item/expiration.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [flag](../-item/flag.html) | [jvm]<br>open var [flag](../-item/flag.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [giftFrom](../-item/gift-from.html) | [jvm]<br>var [giftFrom](../-item/gift-from.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [hands](hands.html) | [jvm]<br>var [hands](hands.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [hp](hp.html) | [jvm]<br>var [hp](hp.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [int](int.html) | [jvm]<br>var [int](int.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [isWearing](is-wearing.html) | [jvm]<br>var [isWearing](is-wearing.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [itemExp](item-exp.html) | [jvm]<br>var [itemExp](item-exp.html): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0F |
| [itemId](../-item/item-id.html) | [jvm]<br>val [itemId](../-item/item-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [itemLevel](item-level.html) | [jvm]<br>var [itemLevel](item-level.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 1 |
| [jump](jump.html) | [jvm]<br>var [jump](jump.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [level](level.html) | [jvm]<br>var [level](level.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [log](../-item/log.html) | [jvm]<br>var [log](../-item/log.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [luk](luk.html) | [jvm]<br>var [luk](luk.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [matk](matk.html) | [jvm]<br>var [matk](matk.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [mdef](mdef.html) | [jvm]<br>var [mdef](mdef.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [mp](mp.html) | [jvm]<br>var [mp](mp.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [owner](../-item/owner.html) | [jvm]<br>var [owner](../-item/owner.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pet](../-item/pet.html) | [jvm]<br>val [pet](../-item/pet.html): [Pet](../-pet/index.html)? |
| [petId](../-item/pet-id.html) | [jvm]<br>val [petId](../-item/pet-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [position](../-item/position.html) | [jvm]<br>var [position](../-item/position.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [quantity](quantity.html) | [jvm]<br>open override var [quantity](quantity.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [ringId](ring-id.html) | [jvm]<br>var [ringId](ring-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [sn](../-item/sn.html) | [jvm]<br>var [sn](../-item/sn.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [speed](speed.html) | [jvm]<br>var [speed](speed.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [str](str.html) | [jvm]<br>var [str](str.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [upgradeSlots](upgrade-slots.html) | [jvm]<br>var [upgradeSlots](upgrade-slots.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [vicious](vicious.html) | [jvm]<br>var [vicious](vicious.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [watk](watk.html) | [jvm]<br>var [watk](watk.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [wdef](wdef.html) | [jvm]<br>var [wdef](wdef.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |

