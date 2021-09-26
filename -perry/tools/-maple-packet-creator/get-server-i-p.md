---
title: getServerIP
---
//[Perry](../../../index.html)/[tools](../index.html)/[MaplePacketCreator](index.html)/[getServerIP](get-server-i-p.html)



# getServerIP



[jvm]\
open fun [getServerIP](get-server-i-p.html)(inetAddr: [InetAddress](https://docs.oracle.com/javase/8/docs/api/java/net/InetAddress.html), port: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), clientId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>



Gets a packet telling the client the IP of the channel server.



#### Return



The server IP packet.



## Parameters


jvm

| | |
|---|---|
| inetAddr | The InetAddress of the requested channel server. |
| port | The port the channel is on. |
| clientId | The ID of the client. |




