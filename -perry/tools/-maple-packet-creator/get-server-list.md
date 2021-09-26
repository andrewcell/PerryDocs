---
title: getServerList
---
//[Perry](../../../index.html)/[tools](../index.html)/[MaplePacketCreator](index.html)/[getServerList](get-server-list.html)



# getServerList



[jvm]\
open fun [getServerList](get-server-list.html)(serverId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), serverName: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), flag: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), eventmsg: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), channelLoad: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Channel](../../net.server.channel/-channel/index.html)>): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>



Gets a packet detailing a server and its channels.



#### Return



The server info packet.



## Parameters


jvm

| | |
|---|---|
| serverId |  |
| serverName | The name of the server. |
| channelLoad | Load of the channel - 1200 seems to be max. |




