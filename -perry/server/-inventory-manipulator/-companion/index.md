---
title: Companion
---
//[Perry](../../../../index.html)/[server](../../index.html)/[InventoryManipulator](../index.html)/[Companion](index.html)



# Companion



[jvm]\
object [Companion](index.html)



## Functions


| Name | Summary |
|---|---|
| [addById](add-by-id.html) | [jvm]<br>fun [addById](add-by-id.html)(c: [Client](../../../client/-client/index.html), itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [addById](add-by-id.html)(c: [Client](../../../client/-client/index.html), itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), expiration: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [addById](add-by-id.html)(c: [Client](../../../client/-client/index.html), itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), owner: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, petId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [addById](add-by-id.html)(c: [Client](../../../client/-client/index.html), itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), owner: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, petid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), expiration: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [addById](add-by-id.html)(c: [Client](../../../client/-client/index.html), itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), owner: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, petId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), flag: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), expiration: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [addFromDrop](add-from-drop.html) | [jvm]<br>fun [addFromDrop](add-from-drop.html)(c: [Client](../../../client/-client/index.html), item: [Item](../../../client.inventory/-item/index.html), show: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [checkSpace](check-space.html) | [jvm]<br>fun [checkSpace](check-space.html)(c: [Client](../../../client/-client/index.html), itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), owner: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [drop](drop.html) | [jvm]<br>fun [drop](drop.html)(c: [Client](../../../client/-client/index.html), _type: [InventoryType](../../../client.inventory/-inventory-type/index.html), src: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html)) |
| [equip](equip.html) | [jvm]<br>fun [equip](equip.html)(c: [Client](../../../client/-client/index.html), src: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), dest: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) |
| [move](move.html) | [jvm]<br>fun [move](move.html)(c: [Client](../../../client/-client/index.html), type: [InventoryType](../../../client.inventory/-inventory-type/index.html), src: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), dest: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) |
| [removeById](remove-by-id.html) | [jvm]<br>fun [removeById](remove-by-id.html)(c: [Client](../../../client/-client/index.html), type: [InventoryType](../../../client.inventory/-inventory-type/index.html), itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), fromDrop: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), consume: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [removeFromSlot](remove-from-slot.html) | [jvm]<br>fun [removeFromSlot](remove-from-slot.html)(c: [Client](../../../client/-client/index.html), type: [InventoryType](../../../client.inventory/-inventory-type/index.html), slot: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), fromDrop: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), consume: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false) |
| [unequip](unequip.html) | [jvm]<br>fun [unequip](unequip.html)(c: [Client](../../../client/-client/index.html), src: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), dest: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) |

