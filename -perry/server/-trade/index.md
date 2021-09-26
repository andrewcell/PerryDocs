---
title: Trade
---
//[Perry](../../../index.html)/[server](../index.html)/[Trade](index.html)



# Trade



[jvm]\
class [Trade](index.html)(number: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), chr: [Character](../../client/-character/index.html))



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [addItem](add-item.html) | [jvm]<br>fun [addItem](add-item.html)(item: [Item](../../client.inventory/-item/index.html)) |
| [cancel](cancel.html) | [jvm]<br>fun [cancel](cancel.html)() |
| [chat](chat.html) | [jvm]<br>fun [chat](chat.html)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), host: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [complete1](complete1.html) | [jvm]<br>fun [complete1](complete1.html)() |
| [complete2](complete2.html) | [jvm]<br>fun [complete2](complete2.html)() |
| [lock](lock.html) | [jvm]<br>fun [lock](lock.html)() |


## Properties


| Name | Summary |
|---|---|
| [chr](chr.html) | [jvm]<br>val [chr](chr.html): [Character](../../client/-character/index.html) |
| [exchangeItems](exchange-items.html) | [jvm]<br>var [exchangeItems](exchange-items.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Item](../../client.inventory/-item/index.html)&gt; |
| [exchangeMeso](exchange-meso.html) | [jvm]<br>var [exchangeMeso](exchange-meso.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [host](host.html) | [jvm]<br>var [host](host.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [items](items.html) | [jvm]<br>val [items](items.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Item](../../client.inventory/-item/index.html)&gt; |
| [locked](locked.html) | [jvm]<br>var [locked](locked.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [meso](meso.html) | [jvm]<br>var [meso](meso.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [number](number.html) | [jvm]<br>val [number](number.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [partner](partner.html) | [jvm]<br>var [partner](partner.html): [Trade](index.html)? = null |

