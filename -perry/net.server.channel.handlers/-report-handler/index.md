---
title: ReportHandler
---
//[Perry](../../../index.html)/[net.server.channel.handlers](../index.html)/[ReportHandler](index.html)



# ReportHandler



[jvm]\
class [ReportHandler](index.html) : [AbstractPacketHandler](../../net/-abstract-packet-handler/index.html)



## Functions


| Name | Summary |
|---|---|
| [addReport](add-report.html) | [jvm]<br>fun [addReport](add-report.html)(reporterId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), victimId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), reason: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), chatLog: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) |
| [handlePacket](handle-packet.html) | [jvm]<br>open override fun [handlePacket](handle-packet.html)(slea: [SeekableLittleEndianAccessor](../../tools.data.input/-seekable-little-endian-accessor/index.html), c: [Client](../../client/-client/index.html)) |
| [validateState](../../net/-abstract-packet-handler/validate-state.html) | [jvm]<br>open override fun [validateState](../../net/-abstract-packet-handler/validate-state.html)(c: [Client](../../client/-client/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

