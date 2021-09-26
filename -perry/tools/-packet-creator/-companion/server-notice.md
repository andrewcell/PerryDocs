---
title: serverNotice
---
//[Perry](../../../../index.html)/[tools](../../index.html)/[PacketCreator](../index.html)/[Companion](index.html)/[serverNotice](server-notice.html)



# serverNotice



[jvm]\
fun [serverNotice](server-notice.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)



Gets a server notice packet.



Possible values for type:<br></br> 0: Notice<br></br> 1: Popup<br></br> 2: Megaphone<br></br> 3: Super Megaphone<br></br> 4: Scrolling message at top<br></br> 5: Pink Text<br></br> 6: Lightblue Text



#### Return



The server notice packet.



## Parameters


jvm

| | |
|---|---|
| type | The type of the notice. |
| message | The message to convey. |




