---
title: client.inventory
---
//[Perry](../../index.html)/[client.inventory](index.html)



# Package client.inventory



## Types


| Name | Summary |
|---|---|
| [Equip](-equip/index.html) | [jvm]<br>class [Equip](-equip/index.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), position: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), upgradeSlots: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) : [Item](-item/index.html) |
| [Inventory](-inventory/index.html) | [jvm]<br>class [Inventory](-inventory/index.html)(type: [InventoryType](-inventory-type/index.html), slotLimit: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) : [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)&lt;[Item](-item/index.html)&gt; |
| [InventoryType](-inventory-type/index.html) | [jvm]<br>enum [InventoryType](-inventory-type/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[InventoryType](-inventory-type/index.html)&gt; |
| [Item](-item/index.html) | [jvm]<br>open class [Item](-item/index.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), position: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), petId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [Comparable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)&lt;[Item](-item/index.html)&gt; |
| [ItemFactory](-item-factory/index.html) | [jvm]<br>enum [ItemFactory](-item-factory/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[ItemFactory](-item-factory/index.html)&gt; |
| [ModifyInventory](-modify-inventory/index.html) | [jvm]<br>class [ModifyInventory](-modify-inventory/index.html)(mode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), item: [Item](-item/index.html)?, oldPosition: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html)) |
| [Pet](-pet/index.html) | [jvm]<br>class [Pet](-pet/index.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), position: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), uniqueId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [Item](-item/index.html) |
| [PetCommand](-pet-command/index.html) | [jvm]<br>data class [PetCommand](-pet-command/index.html)(petId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), probability: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), increase: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [PetDataFactory](-pet-data-factory/index.html) | [jvm]<br>class [PetDataFactory](-pet-data-factory/index.html) |
| [SkinColor](-skin-color/index.html) | [jvm]<br>enum [SkinColor](-skin-color/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[SkinColor](-skin-color/index.html)&gt; |
| [WeaponType](-weapon-type/index.html) | [jvm]<br>enum [WeaponType](-weapon-type/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[WeaponType](-weapon-type/index.html)&gt; |

