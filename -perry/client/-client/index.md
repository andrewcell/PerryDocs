---
title: Client
---
//[Perry](../../../index.html)/[client](../index.html)/[Client](index.html)



# Client



[jvm]\
class [Client](index.html)(**sendCrypto**: [MapleAESOFB](../../tools/-maple-a-e-s-o-f-b/index.html), **receiveCrypto**: [MapleAESOFB](../../tools/-maple-a-e-s-o-f-b/index.html), **session**: IoSession?)



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [announce](announce.html) | [jvm]<br>@[Synchronized](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-synchronized/index.html)()<br>fun [announce](announce.html)(packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)) |
| [banMacs](ban-macs.html) | [jvm]<br>fun [banMacs](ban-macs.html)() |
| [checkBirthDate](check-birth-date.html) | [jvm]<br>fun [checkBirthDate](check-birth-date.html)(date: [Calendar](https://docs.oracle.com/javase/8/docs/api/java/util/Calendar.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [dcConnect](dc-connect.html) | [jvm]<br>fun [dcConnect](dc-connect.html)() |
| [deleteCharacter](delete-character.html) | [jvm]<br>fun [deleteCharacter](delete-character.html)(cid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [disconnect](disconnect.html) | [jvm]<br>fun [disconnect](disconnect.html)(shutdown: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), cashShop: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [finishLogin](finish-login.html) | [jvm]<br>fun [finishLogin](finish-login.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [gainCharacterSlot](gain-character-slot.html) | [jvm]<br>fun [gainCharacterSlot](gain-character-slot.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getChannelServer](get-channel-server.html) | [jvm]<br>fun [getChannelServer](get-channel-server.html)(): [Channel](../../net.server.channel/-channel/index.html)<br>fun [getChannelServer](get-channel-server.html)(channel: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)): [Channel](../../net.server.channel/-channel/index.html) |
| [getCM](get-c-m.html) | [jvm]<br>fun [getCM](get-c-m.html)(): [NPCConversationManager](../../scripting.npc/-n-p-c-conversation-manager/index.html)? |
| [getGReason](get-g-reason.html) | [jvm]<br>fun [getGReason](get-g-reason.html)(): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [getLoginState](get-login-state.html) | [jvm]<br>fun [getLoginState](get-login-state.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getQM](get-q-m.html) | [jvm]<br>fun [getQM](get-q-m.html)(): [QuestActionManager](../../scripting.quest/-quest-action-manager/index.html)? |
| [getScriptEngine](get-script-engine.html) | [jvm]<br>fun [getScriptEngine](get-script-engine.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ScriptEngine](https://docs.oracle.com/javase/8/docs/api/javax/script/ScriptEngine.html)? |
| [getSessionIPAddress](get-session-i-p-address.html) | [jvm]<br>fun [getSessionIPAddress](get-session-i-p-address.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getTempBanCalendar](get-temp-ban-calendar.html) | [jvm]<br>fun [getTempBanCalendar](get-temp-ban-calendar.html)(): [Calendar](https://docs.oracle.com/javase/8/docs/api/java/util/Calendar.html)? |
| [getWorldServer](get-world-server.html) | [jvm]<br>fun [getWorldServer](get-world-server.html)(): [World](../../net.server.world/-world/index.html) |
| [hasBannedIp](has-banned-ip.html) | [jvm]<br>fun [hasBannedIp](has-banned-ip.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hasBannedMac](has-banned-mac.html) | [jvm]<br>fun [hasBannedMac](has-banned-mac.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [loadCharacterNames](load-character-names.html) | [jvm]<br>fun [loadCharacterNames](load-character-names.html)(serverId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)> |
| [loadCharacters](load-characters.html) | [jvm]<br>fun [loadCharacters](load-characters.html)(serverId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Character](../-character/index.html)> |
| [loadMacsIfNecessary](load-macs-if-necessary.html) | [jvm]<br>fun [loadMacsIfNecessary](load-macs-if-necessary.html)() |
| [login](login.html) | [jvm]<br>fun [login](login.html)(login: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), password: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [pongReceived](pong-received.html) | [jvm]<br>fun [pongReceived](pong-received.html)() |
| [removePlayer](remove-player.html) | [jvm]<br>fun [removePlayer](remove-player.html)() |
| [removeScriptEngine](remove-script-engine.html) | [jvm]<br>fun [removeScriptEngine](remove-script-engine.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ScriptEngine](https://docs.oracle.com/javase/8/docs/api/javax/script/ScriptEngine.html)? |
| [sendCharList](send-char-list.html) | [jvm]<br>fun [sendCharList](send-char-list.html)(server: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): WriteFuture? |
| [sendPing](send-ping.html) | [jvm]<br>fun [sendPing](send-ping.html)() |
| [setScriptEngine](set-script-engine.html) | [jvm]<br>fun [setScriptEngine](set-script-engine.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), e: [ScriptEngine](https://docs.oracle.com/javase/8/docs/api/javax/script/ScriptEngine.html)?): [ScriptEngine](https://docs.oracle.com/javase/8/docs/api/javax/script/ScriptEngine.html)? |
| [setTimesByPacketId](set-times-by-packet-id.html) | [jvm]<br>fun [setTimesByPacketId](set-times-by-packet-id.html)(packetId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [updateLoginState](update-login-state.html) | [jvm]<br>fun [updateLoginState](update-login-state.html)(newState: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [accountId](account-id.html) | [jvm]<br>var [accountId](account-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1 |
| [accountName](account-name.html) | [jvm]<br>var [accountName](account-name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [birthday](birthday.html) | [jvm]<br>var [birthday](birthday.html): [Calendar](https://docs.oracle.com/javase/8/docs/api/java/util/Calendar.html)? = null |
| [channel](channel.html) | [jvm]<br>var [channel](channel.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1 |
| [characterSlots](character-slots.html) | [jvm]<br>var [characterSlots](character-slots.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 3 |
| [disconnecting](disconnecting.html) | [jvm]<br>var [disconnecting](disconnecting.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [engines](engines.html) | [jvm]<br>val [engines](engines.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [ScriptEngine](https://docs.oracle.com/javase/8/docs/api/javax/script/ScriptEngine.html)> |
| [gender](gender.html) | [jvm]<br>var [gender](gender.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [gmLevel](gm-level.html) | [jvm]<br>var [gmLevel](gm-level.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [idleTask](idle-task.html) | [jvm]<br>var [idleTask](idle-task.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? = null |
| [isConnector](is-connector.html) | [jvm]<br>var [isConnector](is-connector.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [lastPong](last-pong.html) | [jvm]<br>var [lastPong](last-pong.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0L |
| [lock](lock.html) | [jvm]<br>val [lock](lock.html): [ReentrantLock](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/locks/ReentrantLock.html) |
| [loggedIn](logged-in.html) | [jvm]<br>var [loggedIn](logged-in.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [loginAttempt](login-attempt.html) | [jvm]<br>var [loginAttempt](login-attempt.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [macs](macs.html) | [jvm]<br>val [macs](macs.html): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)> |
| [player](player.html) | [jvm]<br>var [player](player.html): [Character](../-character/index.html)? = null |
| [receiveCrypto](receive-crypto.html) | [jvm]<br>val [receiveCrypto](receive-crypto.html): [MapleAESOFB](../../tools/-maple-a-e-s-o-f-b/index.html) |
| [sendCrypto](send-crypto.html) | [jvm]<br>val [sendCrypto](send-crypto.html): [MapleAESOFB](../../tools/-maple-a-e-s-o-f-b/index.html) |
| [serverTransition](server-transition.html) | [jvm]<br>var [serverTransition](server-transition.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [session](session.html) | [jvm]<br>val [session](session.html): IoSession? |
| [socialNumber](social-number.html) | [jvm]<br>var [socialNumber](social-number.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1234567 |
| [times](times.html) | [jvm]<br>var [times](times.html): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)> |
| [timesCounter](times-counter.html) | [jvm]<br>var [timesCounter](times-counter.html): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)> |
| [world](world.html) | [jvm]<br>var [world](world.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |

