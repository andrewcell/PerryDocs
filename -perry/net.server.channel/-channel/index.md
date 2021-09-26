---
title: Channel
---
//[Perry](../../../index.html)/[net.server.channel](../index.html)/[Channel](index.html)



# Channel



[jvm]\
class [Channel](index.html)(world: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), channelId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))



## Types


| Name | Summary |
|---|---|
| [RespawnMaps](-respawn-maps/index.html) | [jvm]<br>inner class [RespawnMaps](-respawn-maps/index.html) : [Runnable](https://docs.oracle.com/javase/8/docs/api/java/lang/Runnable.html) |


## Functions


| Name | Summary |
|---|---|
| [addHiredMerchant](add-hired-merchant.html) | [jvm]<br>fun [addHiredMerchant](add-hired-merchant.html)(chrId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), h: [HiredMerchant](../../server.maps/-hired-merchant/index.html)) |
| [addPlayer](add-player.html) | [jvm]<br>fun [addPlayer](add-player.html)(chr: [Character](../../client/-character/index.html)) |
| [broadcastGMPacket](broadcast-g-m-packet.html) | [jvm]<br>fun [broadcastGMPacket](broadcast-g-m-packet.html)(data: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)) |
| [broadcastPacket](broadcast-packet.html) | [jvm]<br>fun [broadcastPacket](broadcast-packet.html)(data: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)) |
| [closeAllMerchants](close-all-merchants.html) | [jvm]<br>fun [closeAllMerchants](close-all-merchants.html)() |
| [getConnectedClients](get-connected-clients.html) | [jvm]<br>fun [getConnectedClients](get-connected-clients.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getPartyMembers](get-party-members.html) | [jvm]<br>fun [getPartyMembers](get-party-members.html)(party: [Party](../../net.server.world/-party/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Character](../../client/-character/index.html)&gt; |
| [isConnected](is-connected.html) | [jvm]<br>fun [isConnected](is-connected.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [multiBuddyFind](multi-buddy-find.html) | [jvm]<br>fun [multiBuddyFind](multi-buddy-find.html)(charIdFrom: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), characterIds: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt; |
| [removeHiredMerchant](remove-hired-merchant.html) | [jvm]<br>fun [removeHiredMerchant](remove-hired-merchant.html)(chrId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [removePlayer](remove-player.html) | [jvm]<br>fun [removePlayer](remove-player.html)(chr: [Character](../../client/-character/index.html)): [Character](../../client/-character/index.html)? |
| [shutdown](shutdown.html) | [jvm]<br>fun [shutdown](shutdown.html)() |
| [worldMessage](world-message.html) | [jvm]<br>fun [worldMessage](world-message.html)(m: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [worldMessageYellow](world-message-yellow.html) | [jvm]<br>fun [worldMessageYellow](world-message-yellow.html)(m: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [acceptor](acceptor.html) | [jvm]<br>val [acceptor](acceptor.html): NioSocketAcceptor |
| [channelId](channel-id.html) | [jvm]<br>val [channelId](channel-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [event](event.html) | [jvm]<br>var [event](event.html): [Event](../../server.events.gm/-event/index.html)? = null |
| [eventSM](event-s-m.html) | [jvm]<br>val [eventSM](event-s-m.html): [EventScriptManager](../../scripting.event/-event-script-manager/index.html) |
| [finishedShutdown](finished-shutdown.html) | [jvm]<br>var [finishedShutdown](finished-shutdown.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [hiredMerchants](hired-merchants.html) | [jvm]<br>val [hiredMerchants](hired-merchants.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [HiredMerchant](../../server.maps/-hired-merchant/index.html)&gt; |
| [ip](ip.html) | [jvm]<br>var [ip](ip.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [mapFactory](map-factory.html) | [jvm]<br>val [mapFactory](map-factory.html): [MapFactory](../../server.maps/-map-factory/index.html) |
| [merchantLock](merchant-lock.html) | [jvm]<br>val [merchantLock](merchant-lock.html): [ReentrantReadWriteLock](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/locks/ReentrantReadWriteLock.html) |
| [players](players.html) | [jvm]<br>val [players](players.html): [PlayerStorage](../../net.server/-player-storage/index.html) |
| [port](port.html) | [jvm]<br>var [port](port.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 7575 |
| [serverMessage](server-message.html) | [jvm]<br>var [serverMessage](server-message.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [world](world.html) | [jvm]<br>val [world](world.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

