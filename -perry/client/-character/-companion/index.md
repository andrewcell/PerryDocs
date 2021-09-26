---
title: Companion
---
//[Perry](../../../../index.html)/[client](../../index.html)/[Character](../index.html)/[Companion](index.html)



# Companion



[jvm]\
object [Companion](index.html)



## Types


| Name | Summary |
|---|---|
| [BuffStatValueHolder](-buff-stat-value-holder/index.html) | [jvm]<br>data class [BuffStatValueHolder](-buff-stat-value-holder/index.html)(effect: [StatEffect](../../../server/-stat-effect/index.html), startTime: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), schedule: [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)&lt;*&gt;, value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [CancelCoolDownAction](-cancel-cool-down-action/index.html) | [jvm]<br>class [CancelCoolDownAction](-cancel-cool-down-action/index.html)(target: [Character](../index.html), skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [Runnable](https://docs.oracle.com/javase/8/docs/api/java/lang/Runnable.html) |
| [CoolDownValueHolder](-cool-down-value-holder/index.html) | [jvm]<br>data class [CoolDownValueHolder](-cool-down-value-holder/index.html)(skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startTime: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), length: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), timer: [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)&lt;*&gt;?) |
| [Note](-note/index.html) | [jvm]<br>data class [Note](-note/index.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), from: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), fame: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) |
| [SkillEntry](-skill-entry/index.html) | [jvm]<br>data class [SkillEntry](-skill-entry/index.html)(skillLevel: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), masterLevel: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), expiration: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [ban](ban.html) | [jvm]<br>fun [ban](ban.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), reason: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), accountId: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [checkNameAvailable](check-name-available.html) | [jvm]<br>fun [checkNameAvailable](check-name-available.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getCharacterFromDatabase](get-character-from-database.html) | [jvm]<br>fun [getCharacterFromDatabase](get-character-from-database.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [getDefault](get-default.html) | [jvm]<br>fun [getDefault](get-default.html)(c: [Client](../../-client/index.html)): [Character](../index.html) |
| [getIdByName](get-id-by-name.html) | [jvm]<br>fun [getIdByName](get-id-by-name.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [loadCharFromDatabase](load-char-from-database.html) | [jvm]<br>fun [loadCharFromDatabase](load-char-from-database.html)(charId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), client: [Client](../../-client/index.html), channelServer: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Character](../index.html)? |
| [makeReadable](make-readable.html) | [jvm]<br>fun [makeReadable](make-readable.html)(r: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |


## Properties


| Name | Summary |
|---|---|
| [DEFAULT_ACTION](-d-e-f-a-u-l-t_-a-c-t-i-o-n.html) | [jvm]<br>val [DEFAULT_ACTION](-d-e-f-a-u-l-t_-a-c-t-i-o-n.html): [IntArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int-array/index.html) |
| [DEFAULT_KEY](-d-e-f-a-u-l-t_-k-e-y.html) | [jvm]<br>val [DEFAULT_KEY](-d-e-f-a-u-l-t_-k-e-y.html): [IntArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int-array/index.html) |
| [DEFAULT_TYPE](-d-e-f-a-u-l-t_-t-y-p-e.html) | [jvm]<br>val [DEFAULT_TYPE](-d-e-f-a-u-l-t_-t-y-p-e.html): [IntArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int-array/index.html) |
| [LEVEL_200](-l-e-v-e-l_200.html) | [jvm]<br>const val [LEVEL_200](-l-e-v-e-l_200.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

