---
title: HiredMerchant
---
//[Perry](../../../index.html)/[server.maps](../index.html)/[HiredMerchant](index.html)



# HiredMerchant



[jvm]\
class [HiredMerchant](index.html)(owner: [Character](../../client/-character/index.html), itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [AbstractMapObject](../-abstract-map-object/index.html)



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |
| [SoldItem](-sold-item/index.html) | [jvm]<br>data class [SoldItem](-sold-item/index.html)(buyer: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mesos: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [addItem](add-item.html) | [jvm]<br>fun [addItem](add-item.html)(item: [PlayerShopItem](../../server/-player-shop-item/index.html)) |
| [addVisitor](add-visitor.html) | [jvm]<br>fun [addVisitor](add-visitor.html)(visitor: [Character](../../client/-character/index.html)) |
| [broadcastToVisitors](broadcast-to-visitors.html) | [jvm]<br>fun [broadcastToVisitors](broadcast-to-visitors.html)(packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)) |
| [buy](buy.html) | [jvm]<br>fun [buy](buy.html)(c: [Client](../../client/-client/index.html), item: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [closeShop](close-shop.html) | [jvm]<br>fun [closeShop](close-shop.html)(c: [Client](../../client/-client/index.html), timeout: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [forceClose](force-close.html) | [jvm]<br>fun [forceClose](force-close.html)() |
| [getFreeSlot](get-free-slot.html) | [jvm]<br>fun [getFreeSlot](get-free-slot.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getTimeLeft](get-time-left.html) | [jvm]<br>fun [getTimeLeft](get-time-left.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getVisitorSlot](get-visitor-slot.html) | [jvm]<br>fun [getVisitorSlot](get-visitor-slot.html)(visitor: [Character](../../client/-character/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isOwner](is-owner.html) | [jvm]<br>fun [isOwner](is-owner.html)(chr: [Character](../../client/-character/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeAllVisitors](remove-all-visitors.html) | [jvm]<br>fun [removeAllVisitors](remove-all-visitors.html)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [removeFromSlot](remove-from-slot.html) | [jvm]<br>fun [removeFromSlot](remove-from-slot.html)(slot: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [removeVisitor](remove-visitor.html) | [jvm]<br>fun [removeVisitor](remove-visitor.html)(visitor: [Character](../../client/-character/index.html)) |
| [saveItems](save-items.html) | [jvm]<br>fun [saveItems](save-items.html)(shutdown: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [sendDestroyData](send-destroy-data.html) | [jvm]<br>open override fun [sendDestroyData](send-destroy-data.html)(client: [Client](../../client/-client/index.html)) |
| [sendSpawnData](send-spawn-data.html) | [jvm]<br>open override fun [sendSpawnData](send-spawn-data.html)(client: [Client](../../client/-client/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [channel](channel.html) | [jvm]<br>val [channel](channel.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [description](description.html) | [jvm]<br>val [description](description.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [itemId](item-id.html) | [jvm]<br>val [itemId](item-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [items](items.html) | [jvm]<br>val [items](items.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[PlayerShopItem](../../server/-player-shop-item/index.html)&gt; |
| [map](map.html) | [jvm]<br>var [map](map.html): [GameMap](../-game-map/index.html) |
| [messages](messages.html) | [jvm]<br>val [messages](messages.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;&gt; |
| [objectId](../-abstract-map-object/object-id.html) | [jvm]<br>open override var [objectId](../-abstract-map-object/object-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [objectType](object-type.html) | [jvm]<br>open override val [objectType](object-type.html): [MapObjectType](../-map-object-type/index.html) |
| [open](open.html) | [jvm]<br>var [open](open.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [ownerId](owner-id.html) | [jvm]<br>val [ownerId](owner-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [ownerName](owner-name.html) | [jvm]<br>val [ownerName](owner-name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [position](position.html) | [jvm]<br>open override var [position](position.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [schedule](schedule.html) | [jvm]<br>var [schedule](schedule.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)&lt;*&gt;? |
| [sold](sold.html) | [jvm]<br>val [sold](sold.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[HiredMerchant.SoldItem](-sold-item/index.html)&gt; |
| [start](start.html) | [jvm]<br>val [start](start.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [visitors](visitors.html) | [jvm]<br>val [visitors](visitors.html): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Character](../../client/-character/index.html)?&gt; |
| [world](world.html) | [jvm]<br>val [world](world.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

