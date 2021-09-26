---
title: PacketHandler
---
//[Perry](../../../index.html)/[net](../index.html)/[PacketHandler](index.html)



# PacketHandler



[jvm]\
interface [PacketHandler](index.html)



## Functions


| Name | Summary |
|---|---|
| [handlePacket](handle-packet.html) | [jvm]<br>abstract fun [handlePacket](handle-packet.html)(slea: [SeekableLittleEndianAccessor](../../tools.data.input/-seekable-little-endian-accessor/index.html), c: [Client](../../client/-client/index.html)) |
| [validateState](validate-state.html) | [jvm]<br>abstract fun [validateState](validate-state.html)(c: [Client](../../client/-client/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Inheritors


| Name |
|---|
| [CancelBuffHandler](../../net.server.channel.handlers/-cancel-buff-handler/index.html) |
| [AbstractPacketHandler](../-abstract-packet-handler/index.html) |
| [CustomPacketHandler](../../net.server.handlers/-custom-packet-handler/index.html) |
| [KeepAliveHandler](../../net.server.handlers/-keep-alive-handler/index.html) |
| [LoginRequiringNoOpHandler](../../net.server.handlers/-login-requiring-no-op-handler/index.html) |
| [LoginPasswordHandler](../../net.server.handlers.login/-login-password-handler/index.html) |

