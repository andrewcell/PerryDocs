---
title: moveMonsterResponse
---
//[Perry](../../../../index.html)/[tools](../../index.html)/[PacketCreator](../index.html)/[Companion](index.html)/[moveMonsterResponse](move-monster-response.html)



# moveMonsterResponse



[jvm]\
fun [moveMonsterResponse](move-monster-response.html)(objectId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), moveId: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), currentMp: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), useSkills: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, skillLevel: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)



Gets a response to a move monster packet.



#### Return



The move response packet.



## Parameters


jvm

| | |
|---|---|
| objectId | The ObjectID of the monster being moved. |
| moveId | The movement ID. |
| currentMp | The current MP of the monster. |
| useSkills | Can the monster use skills? |
| skillId | The skill ID for the monster to use. |
| skillLevel | The level of the skill to use. |




