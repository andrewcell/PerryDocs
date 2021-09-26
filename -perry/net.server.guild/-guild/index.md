---
title: Guild
---
//[Perry](../../../index.html)/[net.server.guild](../index.html)/[Guild](index.html)



# Guild



[jvm]\
class [Guild](index.html)(creator: [GuildCharacter](../-guild-character/index.html))



## Types


| Name | Summary |
|---|---|
| [BCOp](-b-c-op/index.html) | [jvm]<br>enum [BCOp](-b-c-op/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[Guild.BCOp](-b-c-op/index.html)&gt; |
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [addGuildMember](add-guild-member.html) | [jvm]<br>fun [addGuildMember](add-guild-member.html)(mgc: [GuildCharacter](../-guild-character/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [broadcast](broadcast.html) | [jvm]<br>fun [broadcast](broadcast.html)(packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)?, exceptionId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = -1, bcop: [Guild.BCOp](-b-c-op/index.html) = BCOp.NONE) |
| [buildNotifications](build-notifications.html) | [jvm]<br>fun [buildNotifications](build-notifications.html)() |
| [changeRank](change-rank.html) | [jvm]<br>fun [changeRank](change-rank.html)(cid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), newRank: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [changeRankTitle](change-rank-title.html) | [jvm]<br>fun [changeRankTitle](change-rank-title.html)(ranks: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;) |
| [disbandGuild](disband-guild.html) | [jvm]<br>fun [disbandGuild](disband-guild.html)() |
| [expelMember](expel-member.html) | [jvm]<br>fun [expelMember](expel-member.html)(init: [GuildCharacter](../-guild-character/index.html), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), cid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [getIncreaseGuildCost](get-increase-guild-cost.html) | [jvm]<br>fun [getIncreaseGuildCost](get-increase-guild-cost.html)(size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getRankTitle](get-rank-title.html) | [jvm]<br>fun [getRankTitle](get-rank-title.html)(rank: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [guildChat](guild-chat.html) | [jvm]<br>fun [guildChat](guild-chat.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), cid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [guildMessage](guild-message.html) | [jvm]<br>fun [guildMessage](guild-message.html)(serverNotice: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)) |
| [increaseCapacity](increase-capacity.html) | [jvm]<br>fun [increaseCapacity](increase-capacity.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [leaveGuild](leave-guild.html) | [jvm]<br>fun [leaveGuild](leave-guild.html)(mgc: [GuildCharacter](../-guild-character/index.html)) |
| [memberLevelJobUpdate](member-level-job-update.html) | [jvm]<br>fun [memberLevelJobUpdate](member-level-job-update.html)(mgc: [GuildCharacter](../-guild-character/index.html)) |
| [setGuildEmblem](set-guild-emblem.html) | [jvm]<br>fun [setGuildEmblem](set-guild-emblem.html)(bg: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), bgColor: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), logo: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), logoColor: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) |
| [setGuildNotice](set-guild-notice.html) | [jvm]<br>fun [setGuildNotice](set-guild-notice.html)(notice: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [setOnline](set-online.html) | [jvm]<br>fun [setOnline](set-online.html)(cid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), online: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), channel: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [writeToDatabase](write-to-database.html) | [jvm]<br>fun [writeToDatabase](write-to-database.html)(disband: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [allianceId](alliance-id.html) | [jvm]<br>var [allianceId](alliance-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [capacity](capacity.html) | [jvm]<br>var [capacity](capacity.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [dirty](dirty.html) | [jvm]<br>var [dirty](dirty.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [gp](gp.html) | [jvm]<br>var [gp](gp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [id](id.html) | [jvm]<br>var [id](id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [leader](leader.html) | [jvm]<br>var [leader](leader.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [logo](logo.html) | [jvm]<br>var [logo](logo.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [logoBG](logo-b-g.html) | [jvm]<br>var [logoBG](logo-b-g.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [logoBGColor](logo-b-g-color.html) | [jvm]<br>var [logoBGColor](logo-b-g-color.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [logoColor](logo-color.html) | [jvm]<br>var [logoColor](logo-color.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [members](members.html) | [jvm]<br>val [members](members.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[GuildCharacter](../-guild-character/index.html)&gt; |
| [name](name.html) | [jvm]<br>var [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [notice](notice.html) | [jvm]<br>var [notice](notice.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [notifications](notifications.html) | [jvm]<br>val [notifications](notifications.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;&gt; |
| [rankTitles](rank-titles.html) | [jvm]<br>val [rankTitles](rank-titles.html): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [signature](signature.html) | [jvm]<br>var [signature](signature.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [world](world.html) | [jvm]<br>val [world](world.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

