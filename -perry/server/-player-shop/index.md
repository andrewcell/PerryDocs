---
title: PlayerShop
---
//[Perry](../../../index.html)/[server](../index.html)/[PlayerShop](index.html)



# PlayerShop



[jvm]\
class [PlayerShop](index.html)(owner: [Character](../../client/-character/index.html), description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [AbstractMapObject](../../server.maps/-abstract-map-object/index.html)



## Functions


| Name | Summary |
|---|---|
| [addItem](add-item.html) | [jvm]<br>fun [addItem](add-item.html)(item: [PlayerShopItem](../-player-shop-item/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [addVisitor](add-visitor.html) | [jvm]<br>fun [addVisitor](add-visitor.html)(visitor: [Character](../../client/-character/index.html)) |
| [banPlayer](ban-player.html) | [jvm]<br>fun [banPlayer](ban-player.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [broadcast](broadcast.html) | [jvm]<br>fun [broadcast](broadcast.html)(packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)) |
| [buy](buy.html) | [jvm]<br>fun [buy](buy.html)(c: [Client](../../client/-client/index.html), item: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html)) |
| [chat](chat.html) | [jvm]<br>fun [chat](chat.html)(c: [Client](../../client/-client/index.html), chat: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [hasFreeSlot](has-free-slot.html) | [jvm]<br>fun [hasFreeSlot](has-free-slot.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isBanned](is-banned.html) | [jvm]<br>fun [isBanned](is-banned.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isOwner](is-owner.html) | [jvm]<br>fun [isOwner](is-owner.html)(c: [Character](../../client/-character/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isVisitor](is-visitor.html) | [jvm]<br>fun [isVisitor](is-visitor.html)(visitor: [Character](../../client/-character/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeItem](remove-item.html) | [jvm]<br>fun [removeItem](remove-item.html)(item: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [PlayerShopItem](../-player-shop-item/index.html) |
| [removeVisitor](remove-visitor.html) | [jvm]<br>fun [removeVisitor](remove-visitor.html)(visitor: [Character](../../client/-character/index.html)) |
| [removeVisitors](remove-visitors.html) | [jvm]<br>fun [removeVisitors](remove-visitors.html)() |
| [sendDestroyData](send-destroy-data.html) | [jvm]<br>open override fun [sendDestroyData](send-destroy-data.html)(client: [Client](../../client/-client/index.html)) |
| [sendShop](send-shop.html) | [jvm]<br>fun [sendShop](send-shop.html)(c: [Client](../../client/-client/index.html)) |
| [sendSpawnData](send-spawn-data.html) | [jvm]<br>open override fun [sendSpawnData](send-spawn-data.html)(client: [Client](../../client/-client/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [description](description.html) | [jvm]<br>val [description](description.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [items](items.html) | [jvm]<br>val [items](items.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[PlayerShopItem](../-player-shop-item/index.html)&gt; |
| [objectId](../../server.maps/-abstract-map-object/object-id.html) | [jvm]<br>open override var [objectId](../../server.maps/-abstract-map-object/object-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [objectType](object-type.html) | [jvm]<br>open override val [objectType](object-type.html): [MapObjectType](../../server.maps/-map-object-type/index.html) |
| [owner](owner.html) | [jvm]<br>val [owner](owner.html): [Character](../../client/-character/index.html) |
| [position](../../server.maps/-abstract-map-object/position.html) | [jvm]<br>open override var [position](../../server.maps/-abstract-map-object/position.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [visitors](visitors.html) | [jvm]<br>val [visitors](visitors.html): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Character](../../client/-character/index.html)?&gt; |

