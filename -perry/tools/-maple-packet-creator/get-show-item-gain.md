---
title: getShowItemGain
---
//[Perry](../../../index.html)/[tools](../index.html)/[MaplePacketCreator](index.html)/[getShowItemGain](get-show-item-gain.html)



# getShowItemGain



[jvm]\
open fun [getShowItemGain](get-show-item-gain.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;



Gets a packet telling the client to show a item gain.



#### Return



The item gain packet.



## Parameters


jvm

| | |
|---|---|
| itemId | The ID of the item gained. |
| quantity | How many items gained. |





[jvm]\
open fun [getShowItemGain](get-show-item-gain.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), inChat: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;



Gets a packet telling the client to show an item gain.



#### Return



The item gain packet.



## Parameters


jvm

| | |
|---|---|
| itemId | The ID of the item gained. |
| quantity | The number of items gained. |
| inChat | Show in the chat window? |




