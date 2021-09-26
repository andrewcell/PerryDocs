---
title: getGMEffect
---
//[Perry](../../../index.html)/[tools](../index.html)/[MaplePacketCreator](index.html)/[getGMEffect](get-g-m-effect.html)



# getGMEffect



[jvm]\
open fun [getGMEffect](get-g-m-effect.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mode: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>



Gets a gm effect packet (ie. hide, banned, etc.) Possible values for type: 0x04: You have successfully blocked access. 0x05: The unblocking has been successful. 0x06 with Mode 0: You have successfully removed the name from the ranks. 0x06 with Mode 1: You have entered an invalid character name. 0x10: GM Hide, mode determines whether or not it is on. 0x1E: Mode 0: Failed to send warning Mode 1: Sent warning 0x13 with Mode 0: + mapid 0x13 with Mode 1: + ch (FF = Unable to find merchant)



#### Return



The gm effect packet



## Parameters


jvm

| | |
|---|---|
| type | The type |
| mode | The mode |




