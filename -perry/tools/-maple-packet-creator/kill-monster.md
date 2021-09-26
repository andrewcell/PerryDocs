---
title: killMonster
---
//[Perry](../../../index.html)/[tools](../index.html)/[MaplePacketCreator](index.html)/[killMonster](kill-monster.html)



# killMonster



[jvm]\
open fun [killMonster](kill-monster.html)(oid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), animation: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;





[jvm]\
open fun [killMonster](kill-monster.html)(oid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), animation: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;



Gets a packet telling the client that a monster was killed.



#### Return



The kill monster packet.



## Parameters


jvm

| | |
|---|---|
| oid | The objectID of the killed monster. |
| animation | 0 = dissapear, 1 = fade out, 2+ = special |




