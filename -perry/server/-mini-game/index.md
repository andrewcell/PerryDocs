---
title: MiniGame
---
//[Perry](../../../index.html)/[server](../index.html)/[MiniGame](index.html)



# MiniGame



[jvm]\
class [MiniGame](index.html)(**owner**: [Character](../../client/-character/index.html), **description**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **locker**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **password**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [AbstractMapObject](../../server.maps/-abstract-map-object/index.html)



## Functions


| Name | Summary |
|---|---|
| [addVisitor](add-visitor.html) | [jvm]<br>fun [addVisitor](add-visitor.html)(visitor: [Character](../../client/-character/index.html)) |
| [banVisitor](ban-visitor.html) | [jvm]<br>fun [banVisitor](ban-visitor.html)() |
| [broadcast](broadcast.html) | [jvm]<br>fun [broadcast](broadcast.html)(packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)) |
| [chat](chat.html) | [jvm]<br>fun [chat](chat.html)(c: [Client](../../client/-client/index.html), chat: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [getCardId](get-card-id.html) | [jvm]<br>fun [getCardId](get-card-id.html)(slot: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [hasFreeSlot](has-free-slot.html) | [jvm]<br>fun [hasFreeSlot](has-free-slot.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isOwner](is-owner.html) | [jvm]<br>fun [isOwner](is-owner.html)(chr: [Character](../../client/-character/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isVisitor](is-visitor.html) | [jvm]<br>fun [isVisitor](is-visitor.html)(chr: [Character](../../client/-character/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeVisitor](remove-visitor.html) | [jvm]<br>fun [removeVisitor](remove-visitor.html)(visitor: [Character](../../client/-character/index.html)) |
| [sendDestroyData](send-destroy-data.html) | [jvm]<br>open override fun [sendDestroyData](send-destroy-data.html)(client: [Client](../../client/-client/index.html)) |
| [sendMatchCard](send-match-card.html) | [jvm]<br>fun [sendMatchCard](send-match-card.html)(c: [Client](../../client/-client/index.html), type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [sendOmok](send-omok.html) | [jvm]<br>fun [sendOmok](send-omok.html)(c: [Client](../../client/-client/index.html), type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [sendSpawnData](send-spawn-data.html) | [jvm]<br>open override fun [sendSpawnData](send-spawn-data.html)(client: [Client](../../client/-client/index.html)) |
| [setOwnerPoints](set-owner-points.html) | [jvm]<br>fun [setOwnerPoints](set-owner-points.html)() |
| [setPiece](set-piece.html) | [jvm]<br>fun [setPiece](set-piece.html)(move1: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), move2: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), chr: [Character](../../client/-character/index.html)) |
| [setVisitorPoints](set-visitor-points.html) | [jvm]<br>fun [setVisitorPoints](set-visitor-points.html)() |
| [shuffleList](shuffle-list.html) | [jvm]<br>fun [shuffleList](shuffle-list.html)() |


## Properties


| Name | Summary |
|---|---|
| [description](description.html) | [jvm]<br>val [description](description.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [firstSlot](first-slot.html) | [jvm]<br>var [firstSlot](first-slot.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [gameType](game-type.html) | [jvm]<br>var [gameType](game-type.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [locker](locker.html) | [jvm]<br>val [locker](locker.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [loser](loser.html) | [jvm]<br>var [loser](loser.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1 |
| [matchesToWin](matches-to-win.html) | [jvm]<br>var [matchesToWin](matches-to-win.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [objectId](index.html#-115388663%2FProperties%2F863300109) | [jvm]<br>open override var [objectId](index.html#-115388663%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [objectType](object-type.html) | [jvm]<br>open override val [objectType](object-type.html): [MapObjectType](../../server.maps/-map-object-type/index.html) |
| [owner](owner.html) | [jvm]<br>val [owner](owner.html): [Character](../../client/-character/index.html) |
| [password](password.html) | [jvm]<br>val [password](password.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [pieceType](piece-type.html) | [jvm]<br>var [pieceType](piece-type.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [position](index.html#438606202%2FProperties%2F863300109) | [jvm]<br>open override var [position](index.html#438606202%2FProperties%2F863300109): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [visitor](visitor.html) | [jvm]<br>var [visitor](visitor.html): [Character](../../client/-character/index.html)? = null |

