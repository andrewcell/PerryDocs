---
title: killMonster
---
//[Perry](../../../../index.html)/[tools](../../index.html)/[PacketCreator](../index.html)/[Companion](index.html)/[killMonster](kill-monster.html)



# killMonster



[jvm]\
fun [killMonster](kill-monster.html)(oid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), animation: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))





[jvm]\
fun [killMonster](kill-monster.html)(oid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), animation: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)



Gets a packet telling the client that a monster was killed.



#### Return



The kill monster packet.



## Parameters


jvm

| | |
|---|---|
| oid | The objectID of the killed monster. |
| animation | 0 = dissapear, 1 = fade out, 2+ = special |




