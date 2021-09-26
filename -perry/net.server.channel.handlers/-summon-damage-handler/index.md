---
title: SummonDamageHandler
---
//[Perry](../../../index.html)/[net.server.channel.handlers](../index.html)/[SummonDamageHandler](index.html)



# SummonDamageHandler



[jvm]\
class [SummonDamageHandler](index.html) : [AbstractPacketHandler](../../net/-abstract-packet-handler/index.html)



## Types


| Name | Summary |
|---|---|
| [SummonAttackEntry](-summon-attack-entry/index.html) | [jvm]<br>data class [SummonAttackEntry](-summon-attack-entry/index.html)(**monsterOid**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **damage**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [handlePacket](handle-packet.html) | [jvm]<br>open override fun [handlePacket](handle-packet.html)(slea: [SeekableLittleEndianAccessor](../../tools.data.input/-seekable-little-endian-accessor/index.html), c: [Client](../../client/-client/index.html)) |
| [validateState](../../net/-abstract-packet-handler/validate-state.html) | [jvm]<br>open override fun [validateState](../../net/-abstract-packet-handler/validate-state.html)(c: [Client](../../client/-client/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

