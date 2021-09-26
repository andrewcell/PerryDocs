---
title: Companion
---
//[Perry](../../../../../index.html)/[server](../../../index.html)/[Cashshop](../../index.html)/[CashItemFactory](../index.html)/[Companion](index.html)



# Companion



[jvm]\
object [Companion](index.html)



## Functions


| Name | Summary |
|---|---|
| [getItem](get-item.html) | [jvm]<br>fun [getItem](get-item.html)(sn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Cashshop.CashItem](../../-cash-item/index.html)? |
| [getPackage](get-package.html) | [jvm]<br>fun [getPackage](get-package.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Item](../../../../client.inventory/-item/index.html)&gt; |
| [isPackage](is-package.html) | [jvm]<br>fun [isPackage](is-package.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Properties


| Name | Summary |
|---|---|
| [items](items.html) | [jvm]<br>val [items](items.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Cashshop.CashItem](../../-cash-item/index.html)&gt; |
| [packages](packages.html) | [jvm]<br>val [packages](packages.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;&gt; |
| [specialCashItems](special-cash-items.html) | [jvm]<br>val [specialCashItems](special-cash-items.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Cashshop.SpecialCashItem](../../-special-cash-item/index.html)&gt; |

