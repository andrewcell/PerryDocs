---
title: getAfterLoginError
---
//[Perry](../../../index.html)/[tools](../index.html)/[MaplePacketCreator](index.html)/[getAfterLoginError](get-after-login-error.html)



# getAfterLoginError



[jvm]\
open fun [getAfterLoginError](get-after-login-error.html)(reason: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;



Gets a login failed packet. Possible values for reason: 2: ID deleted or blocked 3: ID deleted or blocked 4: Incorrect password 5: Not a registered id 6: Trouble logging into the game? 7: Already logged in 8: Trouble logging into the game? 9: Trouble logging into the game? 10: Cannot process so many connections 11: Only users older than 20 can use this channel 12: Trouble logging into the game? 13: Unable to log on as master at this ip 14: Wrong gateway or personal info and weird korean button 15: Processing request with that korean button! 16: Please verify your account through email... 17: Wrong gateway or personal info 21: Please verify your account through email... 23: Crashes 25: Maple Europe notice =[ FUCK YOU NEXON 27: Some weird full client notice, probably for trial versions



#### Return



The login failed packet.



## Parameters


jvm

| | |
|---|---|
| reason | The reason logging in failed. |




