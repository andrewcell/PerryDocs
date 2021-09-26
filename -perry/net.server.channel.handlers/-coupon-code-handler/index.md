---
title: CouponCodeHandler
---
//[Perry](../../../index.html)/[net.server.channel.handlers](../index.html)/[CouponCodeHandler](index.html)



# CouponCodeHandler



[jvm]\
class [CouponCodeHandler](index.html) : [AbstractPacketHandler](../../net/-abstract-packet-handler/index.html)



## Functions


| Name | Summary |
|---|---|
| [getNXCode](get-n-x-code.html) | [jvm]<br>fun [getNXCode](get-n-x-code.html)(code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getNXCodeValid](get-n-x-code-valid.html) | [jvm]<br>fun [getNXCodeValid](get-n-x-code-valid.html)(code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [handlePacket](handle-packet.html) | [jvm]<br>open override fun [handlePacket](handle-packet.html)(slea: [SeekableLittleEndianAccessor](../../tools.data.input/-seekable-little-endian-accessor/index.html), c: [Client](../../client/-client/index.html)) |
| [validateState](../../net/-abstract-packet-handler/validate-state.html) | [jvm]<br>open override fun [validateState](../../net/-abstract-packet-handler/validate-state.html)(c: [Client](../../client/-client/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

