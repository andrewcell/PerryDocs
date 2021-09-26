---
title: Companion
---
//[Perry](../../../../index.html)/[gm](../../index.html)/[GMPacketCreator](../index.html)/[Companion](index.html)



# Companion



[jvm]\
object [Companion](index.html)



## Functions


| Name | Summary |
|---|---|
| [addUser](add-user.html) | [jvm]<br>fun [addUser](add-user.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [chat](chat.html) | [jvm]<br>fun [chat](chat.html)(msg: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [commandResponse](command-response.html) | [jvm]<br>fun [commandResponse](command-response.html)(op: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [keyResponse](key-response.html) | [jvm]<br>fun [keyResponse](key-response.html)(ok: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [playerStats](player-stats.html) | [jvm]<br>fun [playerStats](player-stats.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), job: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), level: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), exp: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), hp: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), mp: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), str: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), dex: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), int: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), luk: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), meso: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [removeUser](remove-user.html) | [jvm]<br>fun [removeUser](remove-user.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [sendLoginResponse](send-login-response.html) | [jvm]<br>fun [sendLoginResponse](send-login-response.html)(loginOk: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), login: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [sendPlayerList](send-player-list.html) | [jvm]<br>fun [sendPlayerList](send-player-list.html)(list: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [sendUserList](send-user-list.html) | [jvm]<br>fun [sendUserList](send-user-list.html)(names: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |

