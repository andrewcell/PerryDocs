---
title: serverNotice
---
//[Perry](../../../index.html)/[tools](../index.html)/[MaplePacketCreator](index.html)/[serverNotice](server-notice.html)



# serverNotice



[jvm]\
open fun [serverNotice](server-notice.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), message: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>



Gets a server notice packet. Possible values for type: 0: [Notice] 1: Popup 2: Megaphone 3: Super Megaphone 4: Scrolling message at top 5: Pink Text 6: Lightblue Text



#### Return



The server notice packet.



## Parameters


jvm

| | |
|---|---|
| type | The type of the notice. |
| message | The message to convey. |





[jvm]\
open fun [serverNotice](server-notice.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), channel: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), message: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>



Gets a server notice packet. Possible values for type: 0: [Notice] 1: Popup 2: Megaphone 3: Super Megaphone 4: Scrolling message at top 5: Pink Text 6: Lightblue Text



#### Return



The server notice packet.



## Parameters


jvm

| | |
|---|---|
| type | The type of the notice. |
| channel | The channel this notice was sent on. |
| message | The message to convey. |





[jvm]\
open fun [serverNotice](server-notice.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), channel: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), message: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), smegaEar: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>




