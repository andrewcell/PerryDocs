---
title: getShowExpGain
---
//[Perry](../../../index.html)/[tools](../index.html)/[MaplePacketCreator](index.html)/[getShowExpGain](get-show-exp-gain.html)



# getShowExpGain



[jvm]\
open fun [getShowExpGain](get-show-exp-gain.html)(gain: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), equip: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), inChat: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), white: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>



Gets a packet telling the client to show an EXP increase.



#### Return



The exp gained packet.



## Parameters


jvm

| | |
|---|---|
| gain | The amount of EXP gained. |
| inChat | In the chat box? |
| white | White text or yellow? |




