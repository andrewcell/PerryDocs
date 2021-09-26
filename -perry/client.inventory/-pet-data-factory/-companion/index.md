---
title: Companion
---
//[Perry](../../../../index.html)/[client.inventory](../../index.html)/[PetDataFactory](../index.html)/[Companion](index.html)



# Companion



[jvm]\
object [Companion](index.html)



## Functions


| Name | Summary |
|---|---|
| [getHunger](get-hunger.html) | [jvm]<br>fun [getHunger](get-hunger.html)(petId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getPetCommand](get-pet-command.html) | [jvm]<br>fun [getPetCommand](get-pet-command.html)(petId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [PetCommand](../../-pet-command/index.html) |


## Properties


| Name | Summary |
|---|---|
| [dataRoot](data-root.html) | [jvm]<br>val [dataRoot](data-root.html): [DataProvider](../../../provider/-data-provider/index.html) |
| [petCommands](pet-commands.html) | [jvm]<br>val [petCommands](pet-commands.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [PetCommand](../../-pet-command/index.html)> |
| [petHunger](pet-hunger.html) | [jvm]<br>val [petHunger](pet-hunger.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> |

