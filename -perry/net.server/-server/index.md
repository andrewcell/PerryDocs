---
title: Server
---
//[Perry](../../../index.html)/[net.server](../index.html)/[Server](index.html)



# Server



[jvm]\
object [Server](index.html) : [Runnable](https://docs.oracle.com/javase/8/docs/api/java/lang/Runnable.html)



## Functions


| Name | Summary |
|---|---|
| [addAlliance](add-alliance.html) | [jvm]<br>fun [addAlliance](add-alliance.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), alliance: [Alliance](../../net.server.guild/-alliance/index.html)) |
| [addGuildMember](add-guild-member.html) | [jvm]<br>fun [addGuildMember](add-guild-member.html)(mgc: [GuildCharacter](../../net.server.guild/-guild-character/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [allianceMessage](alliance-message.html) | [jvm]<br>fun [allianceMessage](alliance-message.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), exception: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), guildEx: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [allSave](all-save.html) | [jvm]<br>fun [allSave](all-save.html)(world: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [autoSave](auto-save.html) | [jvm]<br>fun [autoSave](auto-save.html)(world: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [broadcastGMMessage](broadcast-g-m-message.html) | [jvm]<br>fun [broadcastGMMessage](broadcast-g-m-message.html)(world: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)) |
| [broadcastMessage](broadcast-message.html) | [jvm]<br>fun [broadcastMessage](broadcast-message.html)(world: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)) |
| [connectDatabase](connect-database.html) | [jvm]<br>fun [connectDatabase](connect-database.html)() |
| [deleteGuildCharacter](delete-guild-character.html) | [jvm]<br>fun [deleteGuildCharacter](delete-guild-character.html)(mgc: [GuildCharacter](../../net.server.guild/-guild-character/index.html)) |
| [disbandAlliance](disband-alliance.html) | [jvm]<br>fun [disbandAlliance](disband-alliance.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [getAllChannels](get-all-channels.html) | [jvm]<br>fun [getAllChannels](get-all-channels.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Channel](../../net.server.channel/-channel/index.html)&gt; |
| [getAlliance](get-alliance.html) | [jvm]<br>fun [getAlliance](get-alliance.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Alliance](../../net.server.guild/-alliance/index.html)? |
| [getChannel](get-channel.html) | [jvm]<br>fun [getChannel](get-channel.html)(world: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), channel: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Channel](../../net.server.channel/-channel/index.html) |
| [getChannelServer](get-channel-server.html) | [jvm]<br>fun [getChannelServer](get-channel-server.html)(world: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt; |
| [getChannelsFromWorld](get-channels-from-world.html) | [jvm]<br>fun [getChannelsFromWorld](get-channels-from-world.html)(world: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Channel](../../net.server.channel/-channel/index.html)&gt; |
| [getGuild](get-guild.html) | [jvm]<br>fun [getGuild](get-guild.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Guild](../../net.server.guild/-guild/index.html)?<br>fun [getGuild](get-guild.html)(mgc: [GuildCharacter](../../net.server.guild/-guild-character/index.html)): [Guild](../../net.server.guild/-guild/index.html)?<br>fun [getGuild](get-guild.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mgc: [GuildCharacter](../../net.server.guild/-guild-character/index.html)): [Guild](../../net.server.guild/-guild/index.html)? |
| [getHighestChannelId](get-highest-channel-id.html) | [jvm]<br>fun [getHighestChannelId](get-highest-channel-id.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getIp](get-ip.html) | [jvm]<br>fun [getIp](get-ip.html)(world: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), channel: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [getWorld](get-world.html) | [jvm]<br>fun [getWorld](get-world.html)(world: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [World](../../net.server.world/-world/index.html) |
| [gmChat](gm-chat.html) | [jvm]<br>fun [gmChat](gm-chat.html)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), exclude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [removeChannel](remove-channel.html) | [jvm]<br>fun [removeChannel](remove-channel.html)(worldId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), channel: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [run](run.html) | [jvm]<br>open override fun [run](run.html)() |
| [setGuildMemberOnline](set-guild-member-online.html) | [jvm]<br>fun [setGuildMemberOnline](set-guild-member-online.html)(mgc: [GuildCharacter](../../net.server.guild/-guild-character/index.html), online: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), channel: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [shutdown](shutdown.html) | [jvm]<br>fun [shutdown](shutdown.html)()<br>fun [shutdown](shutdown.html)(restart: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): Runnable |


## Properties


| Name | Summary |
|---|---|
| [acceptor](acceptor.html) | [jvm]<br>val [acceptor](acceptor.html): NioSocketAcceptor |
| [alliances](alliances.html) | [jvm]<br>val [alliances](alliances.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Alliance](../../net.server.guild/-alliance/index.html)&gt; |
| [buffStorage](buff-storage.html) | [jvm]<br>val [buffStorage](buff-storage.html): [PlayerBuffStorage](../-player-buff-storage/index.html) |
| [channels](channels.html) | [jvm]<br>val [channels](channels.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;&gt; |
| [guilds](guilds.html) | [jvm]<br>val [guilds](guilds.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Guild](../../net.server.guild/-guild/index.html)&gt; |
| [online](online.html) | [jvm]<br>var [online](online.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [startTime](start-time.html) | [jvm]<br>val [startTime](start-time.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [subnetInfo](subnet-info.html) | [jvm]<br>val [subnetInfo](subnet-info.html): [Properties](https://docs.oracle.com/javase/8/docs/api/java/util/Properties.html) |
| [worldRecommendedList](world-recommended-list.html) | [jvm]<br>val [worldRecommendedList](world-recommended-list.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)&gt;&gt; |
| [worlds](worlds.html) | [jvm]<br>val [worlds](worlds.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[World](../../net.server.world/-world/index.html)&gt; |

