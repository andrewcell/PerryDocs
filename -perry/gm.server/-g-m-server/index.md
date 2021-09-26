---
title: GMServer
---
//[Perry](../../../index.html)/[gm.server](../index.html)/[GMServer](index.html)



# GMServer



[jvm]\
object [GMServer](index.html)



## Functions


| Name | Summary |
|---|---|
| [addInGame](add-in-game.html) | [jvm]<br>fun [addInGame](add-in-game.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), session: IoSession) |
| [addOutGame](add-out-game.html) | [jvm]<br>fun [addOutGame](add-out-game.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), session: IoSession): IoSession? |
| [broadcastInGame](broadcast-in-game.html) | [jvm]<br>fun [broadcastInGame](broadcast-in-game.html)(packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)) |
| [broadcastOutGame](broadcast-out-game.html) | [jvm]<br>fun [broadcastOutGame](broadcast-out-game.html)(packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), exclude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) |
| [contains](contains.html) | [jvm]<br>operator fun [contains](contains.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getUserList](get-user-list.html) | [jvm]<br>fun [getUserList](get-user-list.html)(exclude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)> |
| [removeInGame](remove-in-game.html) | [jvm]<br>fun [removeInGame](remove-in-game.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [removeOutGame](remove-out-game.html) | [jvm]<br>fun [removeOutGame](remove-out-game.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [shutdown](shutdown.html) | [jvm]<br>fun [shutdown](shutdown.html)() |
| [startGMServer](start-g-m-server.html) | [jvm]<br>fun [startGMServer](start-g-m-server.html)() |


## Properties


| Name | Summary |
|---|---|
| [acceptor](acceptor.html) | [jvm]<br>val [acceptor](acceptor.html): NioSocketAcceptor |
| [inGame](in-game.html) | [jvm]<br>val [inGame](in-game.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), IoSession> |
| [KEYWORD](-k-e-y-w-o-r-d.html) | [jvm]<br>const val [KEYWORD](-k-e-y-w-o-r-d.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [outGame](out-game.html) | [jvm]<br>val [outGame](out-game.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), IoSession> |
| [started](started.html) | [jvm]<br>var [started](started.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |

