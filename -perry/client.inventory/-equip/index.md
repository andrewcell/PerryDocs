---
title: Equip
---
//[Perry](../../../index.html)/[client.inventory](../index.html)/[Equip](index.html)



# Equip



[jvm]\
class [Equip](index.html)(**id**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **position**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), **upgradeSlots**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) : [Item](../-item/index.html)



## Types


| Name | Summary |
|---|---|
| [ScrollResult](-scroll-result/index.html) | [jvm]<br>enum [ScrollResult](-scroll-result/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Equip.ScrollResult](-scroll-result/index.html)> |


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
| [cashId](index.html#-1617686726%2FProperties%2F863300109) | [jvm]<br>var [cashId](index.html#-1617686726%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [dex](dex.html) | [jvm]<br>var [dex](dex.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [expiration](index.html#557239769%2FProperties%2F863300109) | [jvm]<br>var [expiration](index.html#557239769%2FProperties%2F863300109): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [flag](index.html#-1765833732%2FProperties%2F863300109) | [jvm]<br>open var [flag](index.html#-1765833732%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [giftFrom](index.html#-1501866834%2FProperties%2F863300109) | [jvm]<br>var [giftFrom](index.html#-1501866834%2FProperties%2F863300109): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [hands](hands.html) | [jvm]<br>var [hands](hands.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [hp](hp.html) | [jvm]<br>var [hp](hp.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [int](int.html) | [jvm]<br>var [int](int.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [isWearing](is-wearing.html) | [jvm]<br>var [isWearing](is-wearing.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [itemExp](item-exp.html) | [jvm]<br>var [itemExp](item-exp.html): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0F |
| [itemId](index.html#-1685052582%2FProperties%2F863300109) | [jvm]<br>val [itemId](index.html#-1685052582%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [itemLevel](item-level.html) | [jvm]<br>var [itemLevel](item-level.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 1 |
| [jump](jump.html) | [jvm]<br>var [jump](jump.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [level](level.html) | [jvm]<br>var [level](level.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [log](index.html#-354052754%2FProperties%2F863300109) | [jvm]<br>var [log](index.html#-354052754%2FProperties%2F863300109): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)> |
| [luk](luk.html) | [jvm]<br>var [luk](luk.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [matk](matk.html) | [jvm]<br>var [matk](matk.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [mdef](mdef.html) | [jvm]<br>var [mdef](mdef.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [mp](mp.html) | [jvm]<br>var [mp](mp.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [owner](index.html#825157535%2FProperties%2F863300109) | [jvm]<br>var [owner](index.html#825157535%2FProperties%2F863300109): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pet](index.html#-1995947021%2FProperties%2F863300109) | [jvm]<br>val [pet](index.html#-1995947021%2FProperties%2F863300109): [Pet](../-pet/index.html)? |
| [petId](index.html#-1872540264%2FProperties%2F863300109) | [jvm]<br>val [petId](index.html#-1872540264%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [position](index.html#1131699039%2FProperties%2F863300109) | [jvm]<br>var [position](index.html#1131699039%2FProperties%2F863300109): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [quantity](quantity.html) | [jvm]<br>open override var [quantity](quantity.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [ringId](ring-id.html) | [jvm]<br>var [ringId](ring-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [sn](index.html#692805293%2FProperties%2F863300109) | [jvm]<br>var [sn](index.html#692805293%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [speed](speed.html) | [jvm]<br>var [speed](speed.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [str](str.html) | [jvm]<br>var [str](str.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [upgradeSlots](upgrade-slots.html) | [jvm]<br>var [upgradeSlots](upgrade-slots.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [vicious](vicious.html) | [jvm]<br>var [vicious](vicious.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [watk](watk.html) | [jvm]<br>var [watk](watk.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |
| [wdef](wdef.html) | [jvm]<br>var [wdef](wdef.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 0 |

