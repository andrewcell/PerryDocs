---
title: blockedMessage
---
//[Perry](../../../index.html)/[tools](../index.html)/[MaplePacketCreator](index.html)/[blockedMessage](blocked-message.html)



# blockedMessage



[jvm]\
open fun [blockedMessage](blocked-message.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;



Gets a "block" packet (ie. the cash shop is unavailable, etc) Possible values for type: 1: The portal is closed for now. 2: You cannot go to that place. 3: Unable to approach due to the force of the ground. 4: You cannot teleport to or on this map. 5: Unable to approach due to the force of the ground. 6: This map can only be entered by party members. 7: The Cash Shop is currently not available. Stay tuned...



#### Return



The "block" packet.



## Parameters


jvm

| | |
|---|---|
| type | The type |




