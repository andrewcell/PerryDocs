---
title: giveFameErrorResponse
---
//[Perry](../../../../index.html)/[tools](../../index.html)/[PacketCreator](../index.html)/[Companion](index.html)/[giveFameErrorResponse](give-fame-error-response.html)



# giveFameErrorResponse



[jvm]\
fun [giveFameErrorResponse](give-fame-error-response.html)(status: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)



status can be: <br></br> 0: ok, use giveFameResponse<br></br> 1: the username is incorrectly entered<br></br> 2: users under level 15 are unable to toggle with fame.<br></br> 3: can't raise or drop fame anymore today.<br></br> 4: can't raise or drop fame for this character for this month anymore.<br></br> 5: received fame, use receiveFame()<br></br> 6: level of fame neither has been raised nor dropped due to an unexpected error



#### Return



## Parameters


jvm

| | |
|---|---|
| status |  |




