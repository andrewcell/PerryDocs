---
title: BBSOperationHandler
---
//[Perry](../../../index.html)/[net.server.channel.handlers](../index.html)/[BBSOperationHandler](index.html)



# BBSOperationHandler



[jvm]\
class [BBSOperationHandler](index.html) : [AbstractPacketHandler](../../net/-abstract-packet-handler/index.html)



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [correctLength](correct-length.html) | [jvm]<br>fun [correctLength](correct-length.html)(input: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), maxSize: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [handlePacket](handle-packet.html) | [jvm]<br>open override fun [handlePacket](handle-packet.html)(slea: [SeekableLittleEndianAccessor](../../tools.data.input/-seekable-little-endian-accessor/index.html), c: [Client](../../client/-client/index.html)) |
| [validateState](../../net/-abstract-packet-handler/validate-state.html) | [jvm]<br>open override fun [validateState](../../net/-abstract-packet-handler/validate-state.html)(c: [Client](../../client/-client/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

