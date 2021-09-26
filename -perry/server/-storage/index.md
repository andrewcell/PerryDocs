---
title: Storage
---
//[Perry](../../../index.html)/[server](../index.html)/[Storage](index.html)



# Storage



[jvm]\
class [Storage](index.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), slots: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), meso: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [close](close.html) | [jvm]<br>fun [close](close.html)() |
| [gainSlots](gain-slots.html) | [jvm]<br>fun [gainSlots](gain-slots.html)(slots: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getItem](get-item.html) | [jvm]<br>fun [getItem](get-item.html)(slot: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)): [Item](../../client.inventory/-item/index.html) |
| [getSlot](get-slot.html) | [jvm]<br>fun [getSlot](get-slot.html)(type: [InventoryType](../../client.inventory/-inventory-type/index.html), slot: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [isFull](is-full.html) | [jvm]<br>fun [isFull](is-full.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [saveToDatabase](save-to-database.html) | [jvm]<br>fun [saveToDatabase](save-to-database.html)() |
| [sendMeso](send-meso.html) | [jvm]<br>fun [sendMeso](send-meso.html)(c: [Client](../../client/-client/index.html)) |
| [sendStorage](send-storage.html) | [jvm]<br>fun [sendStorage](send-storage.html)(c: [Client](../../client/-client/index.html), npcId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [sendStored](send-stored.html) | [jvm]<br>fun [sendStored](send-stored.html)(c: [Client](../../client/-client/index.html), type: [InventoryType](../../client.inventory/-inventory-type/index.html)) |
| [sendTakenOut](send-taken-out.html) | [jvm]<br>fun [sendTakenOut](send-taken-out.html)(c: [Client](../../client/-client/index.html), type: [InventoryType](../../client.inventory/-inventory-type/index.html)) |
| [store](store.html) | [jvm]<br>fun [store](store.html)(item: [Item](../../client.inventory/-item/index.html)) |
| [takeOut](take-out.html) | [jvm]<br>fun [takeOut](take-out.html)(slot: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)): [Item](../../client.inventory/-item/index.html) |


## Properties


| Name | Summary |
|---|---|
| [id](id.html) | [jvm]<br>val [id](id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [items](items.html) | [jvm]<br>val [items](items.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Item](../../client.inventory/-item/index.html)&gt; |
| [meso](meso.html) | [jvm]<br>var [meso](meso.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [slots](slots.html) | [jvm]<br>var [slots](slots.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |

