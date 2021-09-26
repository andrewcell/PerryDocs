---
title: reportResponse
---
//[Perry](../../../index.html)/[tools](../index.html)/[MaplePacketCreator](index.html)/[reportResponse](report-response.html)



# reportResponse



[jvm]\
open fun [reportResponse](report-response.html)(mode: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;



Sends a report response Possible values for mode: 0: You have succesfully reported the user. 1: Unable to locate the user. 2: You may only report users 10 times a day. 3: You have been reported to the GM's by a user. 4: Your request did not go through for unknown reasons. Please try again later.



#### Return



Report Reponse packet



## Parameters


jvm

| | |
|---|---|
| mode | The mode |




