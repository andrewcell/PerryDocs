---
title: Inventory
---
//[Perry](../../../index.html)/[client.inventory](../index.html)/[Inventory](index.html)



# Inventory



[jvm]\
class [Inventory](index.html)(**type**: [InventoryType](../-inventory-type/index.html), **slotLimit**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) : [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)<[Item](../-item/index.html)>



## Functions


| Name | Summary |
|---|---|
| [addFromDatabase](add-from-database.html) | [jvm]<br>fun [addFromDatabase](add-from-database.html)(item: [Item](../-item/index.html)) |
| [addItem](add-item.html) | [jvm]<br>fun [addItem](add-item.html)(item: [Item](../-item/index.html)?): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [allInventories](all-inventories.html) | [jvm]<br>fun [allInventories](all-inventories.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Inventory](index.html)> |
| [countById](count-by-id.html) | [jvm]<br>fun [countById](count-by-id.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [findByCashId](find-by-cash-id.html) | [jvm]<br>fun [findByCashId](find-by-cash-id.html)(cashId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Item](../-item/index.html)? |
| [findById](find-by-id.html) | [jvm]<br>fun [findById](find-by-id.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Item](../-item/index.html)? |
| [forEach](index.html#-1505148507%2FFunctions%2F863300109) | [jvm]<br>open fun [forEach](index.html#-1505148507%2FFunctions%2F863300109)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Item](../-item/index.html)>) |
| [getItem](get-item.html) | [jvm]<br>fun [getItem](get-item.html)(slot: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)): [Item](../-item/index.html)? |
| [getNextFreeSlot](get-next-free-slot.html) | [jvm]<br>fun [getNextFreeSlot](get-next-free-slot.html)(): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [getNumFreeSlot](get-num-free-slot.html) | [jvm]<br>fun [getNumFreeSlot](get-num-free-slot.html)(): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [isEquipInventory](is-equip-inventory.html) | [jvm]<br>fun [isEquipInventory](is-equip-inventory.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isExtendableInventory](is-extendable-inventory.html) | [jvm]<br>fun [isExtendableInventory](is-extendable-inventory.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isFull](is-full.html) | [jvm]<br>fun [isFull](is-full.html)(margin: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [iterator](iterator.html) | [jvm]<br>open operator override fun [iterator](iterator.html)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Item](../-item/index.html)> |
| [list](list.html) | [jvm]<br>fun [list](list.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Item](../-item/index.html)> |
| [listById](list-by-id.html) | [jvm]<br>fun [listById](list-by-id.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Item](../-item/index.html)> |
| [move](move.html) | [jvm]<br>fun [move](move.html)(sSlot: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), dSlot: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), slotMax: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html)) |
| [removeItem](remove-item.html) | [jvm]<br>fun [removeItem](remove-item.html)(slot: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 1, allowZero: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false) |
| [removeSlot](remove-slot.html) | [jvm]<br>fun [removeSlot](remove-slot.html)(slot: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)): [Item](../-item/index.html)? |
| [spliterator](../../provider.wz/-x-m-l-dom-data/index.html#-1387152138%2FFunctions%2F863300109) | [jvm]<br>open fun [spliterator](../../provider.wz/-x-m-l-dom-data/index.html#-1387152138%2FFunctions%2F863300109)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Item](../-item/index.html)> |


## Properties


| Name | Summary |
|---|---|
| [checked](checked.html) | [jvm]<br>var [checked](checked.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [inventory](inventory.html) | [jvm]<br>val [inventory](inventory.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), [Item](../-item/index.html)> |
| [slotLimit](slot-limit.html) | [jvm]<br>var [slotLimit](slot-limit.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 96 |
| [type](type.html) | [jvm]<br>val [type](type.html): [InventoryType](../-inventory-type/index.html) |

