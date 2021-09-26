---
title: Messenger
---
//[Perry](../../../index.html)/[net.server.world](../index.html)/[Messenger](index.html)



# Messenger



[jvm]\
class [Messenger](index.html)(**id**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **chr**: [MessengerCharacter](../-messenger-character/index.html))



## Functions


| Name | Summary |
|---|---|
| [addMember](add-member.html) | [jvm]<br>fun [addMember](add-member.html)(member: [MessengerCharacter](../-messenger-character/index.html)) |
| [getLowestPosition](get-lowest-position.html) | [jvm]<br>fun [getLowestPosition](get-lowest-position.html)(set: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getPositionByName](get-position-by-name.html) | [jvm]<br>fun [getPositionByName](get-position-by-name.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [removeMember](remove-member.html) | [jvm]<br>fun [removeMember](remove-member.html)(member: [MessengerCharacter](../-messenger-character/index.html), position: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [silentAddMember](silent-add-member.html) | [jvm]<br>fun [silentAddMember](silent-add-member.html)(member: [MessengerCharacter](../-messenger-character/index.html), position: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [silentRemoveMember](silent-remove-member.html) | [jvm]<br>fun [silentRemoveMember](silent-remove-member.html)(member: [MessengerCharacter](../-messenger-character/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Properties


| Name | Summary |
|---|---|
| [id](id.html) | [jvm]<br>val [id](id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [members](members.html) | [jvm]<br>val [members](members.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[MessengerCharacter](../-messenger-character/index.html)> |
| [pos](pos.html) | [jvm]<br>val [pos](pos.html): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?> |

