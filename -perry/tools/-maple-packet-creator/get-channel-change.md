---
title: getChannelChange
---
//[Perry](../../../index.html)/[tools](../index.html)/[MaplePacketCreator](index.html)/[getChannelChange](get-channel-change.html)



# getChannelChange



[jvm]\
open fun [getChannelChange](get-channel-change.html)(inetAddr: [InetAddress](https://docs.oracle.com/javase/8/docs/api/java/net/InetAddress.html), port: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;



Gets a packet telling the client the IP of the new channel.



#### Return



The server IP packet.



## Parameters


jvm

| | |
|---|---|
| inetAddr | The InetAddress of the requested channel server. |
| port | The port the channel is on. |




