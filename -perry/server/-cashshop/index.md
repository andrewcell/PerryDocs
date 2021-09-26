---
title: Cashshop
---
//[Perry](../../../index.html)/[server](../index.html)/[Cashshop](index.html)



# Cashshop



[jvm]\
class [Cashshop](index.html)(accountId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), characterId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))



## Types


| Name | Summary |
|---|---|
| [CashItem](-cash-item/index.html) | [jvm]<br>data class [CashItem](-cash-item/index.html)(sn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), price: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), period: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), count: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), onSale: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [CashItemFactory](-cash-item-factory/index.html) | [jvm]<br>class [CashItemFactory](-cash-item-factory/index.html) |
| [SpecialCashItem](-special-cash-item/index.html) | [jvm]<br>data class [SpecialCashItem](-special-cash-item/index.html)(sn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), modifier: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), info: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [addToInventory](add-to-inventory.html) | [jvm]<br>fun [addToInventory](add-to-inventory.html)(item: [Item](../../client.inventory/-item/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [addToWishList](add-to-wish-list.html) | [jvm]<br>fun [addToWishList](add-to-wish-list.html)(sn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [decreaseNotes](decrease-notes.html) | [jvm]<br>fun [decreaseNotes](decrease-notes.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [findByCashId](find-by-cash-id.html) | [jvm]<br>fun [findByCashId](find-by-cash-id.html)(cashId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Item](../../client.inventory/-item/index.html)? |
| [gainCash](gain-cash.html) | [jvm]<br>fun [gainCash](gain-cash.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), cash: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [getCash](get-cash.html) | [jvm]<br>fun [getCash](get-cash.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [gift](gift.html) | [jvm]<br>fun [gift](gift.html)(recipient: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), from: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), sn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), ringId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = -1) |
| [loadGifts](load-gifts.html) | [jvm]<br>fun [loadGifts](load-gifts.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[Item](../../client.inventory/-item/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;&gt; |
| [removeFromInventory](remove-from-inventory.html) | [jvm]<br>fun [removeFromInventory](remove-from-inventory.html)(item: [Item](../../client.inventory/-item/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [save](save.html) | [jvm]<br>fun [save](save.html)() |


## Properties


| Name | Summary |
|---|---|
| [accountId](account-id.html) | [jvm]<br>val [accountId](account-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [characterId](character-id.html) | [jvm]<br>val [characterId](character-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [factory](factory.html) | [jvm]<br>val [factory](factory.html): [ItemFactory](../../client.inventory/-item-factory/index.html) |
| [inventory](inventory.html) | [jvm]<br>val [inventory](inventory.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Item](../../client.inventory/-item/index.html)&gt; |
| [mPoint](m-point.html) | [jvm]<br>var [mPoint](m-point.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [notes](notes.html) | [jvm]<br>var [notes](notes.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [nxCredit](nx-credit.html) | [jvm]<br>var [nxCredit](nx-credit.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [nxPrepaid](nx-prepaid.html) | [jvm]<br>var [nxPrepaid](nx-prepaid.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [opened](opened.html) | [jvm]<br>var [opened](opened.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [wishList](wish-list.html) | [jvm]<br>val [wishList](wish-list.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt; |

