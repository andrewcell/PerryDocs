---
title: ItemFactory
---
//[Perry](../../../index.html)/[client.inventory](../index.html)/[ItemFactory](index.html)



# ItemFactory



[jvm]\
enum [ItemFactory](index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[ItemFactory](index.html)&gt;



## Entries


| | |
|---|---|
| [MERCHANT](-m-e-r-c-h-a-n-t/index.html) | [jvm]<br>[MERCHANT](-m-e-r-c-h-a-n-t/index.html)(6, false) |
| [CASH_ARAN](-c-a-s-h_-a-r-a-n/index.html) | [jvm]<br>[CASH_ARAN](-c-a-s-h_-a-r-a-n/index.html)(5, false) |
| [CASH_CYGNUS](-c-a-s-h_-c-y-g-n-u-s/index.html) | [jvm]<br>[CASH_CYGNUS](-c-a-s-h_-c-y-g-n-u-s/index.html)(4, false) |
| [CASH_EXPLORER](-c-a-s-h_-e-x-p-l-o-r-e-r/index.html) | [jvm]<br>[CASH_EXPLORER](-c-a-s-h_-e-x-p-l-o-r-e-r/index.html)(3, true) |
| [STORAGE](-s-t-o-r-a-g-e/index.html) | [jvm]<br>[STORAGE](-s-t-o-r-a-g-e/index.html)(2, true) |
| [INVENTORY](-i-n-v-e-n-t-o-r-y/index.html) | [jvm]<br>[INVENTORY](-i-n-v-e-n-t-o-r-y/index.html)(1, false) |


## Functions


| Name | Summary |
|---|---|
| [loadItems](load-items.html) | [jvm]<br>fun [loadItems](load-items.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), login: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[Item](../-item/index.html), [InventoryType](../-inventory-type/index.html)&gt;&gt; |
| [saveItems](save-items.html) | [jvm]<br>@[Synchronized](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-synchronized/index.html)<br>fun [saveItems](save-items.html)(items: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[Item](../-item/index.html), [InventoryType](../-inventory-type/index.html)&gt;&gt;, id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [account](account.html) | [jvm]<br>val [account](account.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [name](../../tools.settings/-database-type/-my-s-q-l/index.html#-372974862%2FProperties%2F863300109) | [jvm]<br>val [name](../../tools.settings/-database-type/-my-s-q-l/index.html#-372974862%2FProperties%2F863300109): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ordinal](../../tools.settings/-database-type/-my-s-q-l/index.html#-739389684%2FProperties%2F863300109) | [jvm]<br>val [ordinal](../../tools.settings/-database-type/-my-s-q-l/index.html#-739389684%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [value](value.html) | [jvm]<br>val [value](value.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

