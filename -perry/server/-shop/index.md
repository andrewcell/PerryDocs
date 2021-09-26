---
title: Shop
---
//[Perry](../../../index.html)/[server](../index.html)/[Shop](index.html)



# Shop



[jvm]\
class [Shop](index.html)(**id**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **npcId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [addItem](add-item.html) | [jvm]<br>fun [addItem](add-item.html)(item: [ShopItem](../-shop-item/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [buy](buy.html) | [jvm]<br>fun [buy](buy.html)(c: [Client](../../client/-client/index.html), slot: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html)) |
| [recharge](recharge.html) | [jvm]<br>fun [recharge](recharge.html)(c: [Client](../../client/-client/index.html), slot: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) |
| [sell](sell.html) | [jvm]<br>fun [sell](sell.html)(c: [Client](../../client/-client/index.html), type: [InventoryType](../../client.inventory/-inventory-type/index.html), slot: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html)) |
| [sendShop](send-shop.html) | [jvm]<br>fun [sendShop](send-shop.html)(c: [Client](../../client/-client/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [id](id.html) | [jvm]<br>val [id](id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [npcId](npc-id.html) | [jvm]<br>val [npcId](npc-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

