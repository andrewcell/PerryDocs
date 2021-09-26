---
title: getLoginFailed
---
//[Perry](../../../index.html)/[tools](../index.html)/[MaplePacketCreator](index.html)/[getLoginFailed](get-login-failed.html)



# getLoginFailed



[jvm]\
open fun [getLoginFailed](get-login-failed.html)(reason: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>



Gets a login failed packet. Possible values for reason: 3: ID deleted or blocked 4: Incorrect password 5: Not a registered id 6: System error 7: Already logged in 8: System error 9: System error 10: Cannot process so many connections 11: Only users older than 20 can use this channel 13: Unable to log on as master at this ip 14: Wrong gateway or personal info and weird korean button 15: Processing request with that korean button! 16: Please verify your account through email... 17: Wrong gateway or personal info 21: Please verify your account through email... 23: License agreement 25: Maple Europe notice =[ FUCK YOU NEXON 27: Some weird full client notice, probably for trial versions



#### Return



The login failed packet.



## Parameters


jvm

| | |
|---|---|
| reason | The reason logging in failed. |




