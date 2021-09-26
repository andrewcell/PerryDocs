---
title: BuddyList
---
//[Perry](../../../index.html)/[client](../index.html)/[BuddyList](index.html)



# BuddyList



[jvm]\
class [BuddyList](index.html)(**capacity**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))



## Types


| Name | Summary |
|---|---|
| [BuddyAddResult](-buddy-add-result/index.html) | [jvm]<br>enum [BuddyAddResult](-buddy-add-result/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[BuddyList.BuddyAddResult](-buddy-add-result/index.html)> |
| [BuddyOperation](-buddy-operation/index.html) | [jvm]<br>enum [BuddyOperation](-buddy-operation/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[BuddyList.BuddyOperation](-buddy-operation/index.html)> |


## Functions


| Name | Summary |
|---|---|
| [addBuddyRequest](add-buddy-request.html) | [jvm]<br>fun [addBuddyRequest](add-buddy-request.html)(c: [Client](../-client/index.html), cidFrom: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), nameFrom: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), channelFrom: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [addEntry](add-entry.html) | [jvm]<br>fun [addEntry](add-entry.html)(e: [BuddyListEntry](../-buddy-list-entry/index.html)): [BuddyListEntry](../-buddy-list-entry/index.html)? |
| [contains](contains.html) | [jvm]<br>fun [contains](contains.html)(characterId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [containsVisible](contains-visible.html) | [jvm]<br>fun [containsVisible](contains-visible.html)(characterId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getBuddyIds](get-buddy-ids.html) | [jvm]<br>fun [getBuddyIds](get-buddy-ids.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> |
| [getEntry](get-entry.html) | [jvm]<br>fun [getEntry](get-entry.html)(cId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [BuddyListEntry](../-buddy-list-entry/index.html)?<br>fun [getEntry](get-entry.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [BuddyListEntry](../-buddy-list-entry/index.html)? |
| [isFull](is-full.html) | [jvm]<br>fun [isFull](is-full.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [loadFromDatabase](load-from-database.html) | [jvm]<br>fun [loadFromDatabase](load-from-database.html)(characterId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [pollPendingRequest](poll-pending-request.html) | [jvm]<br>fun [pollPendingRequest](poll-pending-request.html)(): [CharacterNameAndId](../-character-name-and-id/index.html) |
| [remove](remove.html) | [jvm]<br>fun [remove](remove.html)(characterId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [BuddyListEntry](../-buddy-list-entry/index.html)? |


## Properties


| Name | Summary |
|---|---|
| [buddies](buddies.html) | [jvm]<br>val [buddies](buddies.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [BuddyListEntry](../-buddy-list-entry/index.html)> |
| [capacity](capacity.html) | [jvm]<br>var [capacity](capacity.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [pendingRequests](pending-requests.html) | [jvm]<br>val [pendingRequests](pending-requests.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[CharacterNameAndId](../-character-name-and-id/index.html)> |

