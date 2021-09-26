---
title: client
---
//[Perry](../../index.html)/[client](index.html)



# Package client



## Types


| Name | Summary |
|---|---|
| [AllDiseaseValueHolder](-all-disease-value-holder/index.html) | [jvm]<br>data class [AllDiseaseValueHolder](-all-disease-value-holder/index.html)(**debuff**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Disease](-disease/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>>, **skill**: [MobSkill](../server.life/-mob-skill/index.html)) |
| [BuddyList](-buddy-list/index.html) | [jvm]<br>class [BuddyList](-buddy-list/index.html)(**capacity**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [BuddyListEntry](-buddy-list-entry/index.html) | [jvm]<br>data class [BuddyListEntry](-buddy-list-entry/index.html)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **group**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **characterId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **channel**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **visible**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [BuffStat](-buff-stat/index.html) | [jvm]<br>enum [BuffStat](-buff-stat/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[BuffStat](-buff-stat/index.html)> |
| [Character](-character/index.html) | [jvm]<br>class [Character](-character/index.html)(**world**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **accountId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **map**: [GameMap](../server.maps/-game-map/index.html), **client**: [Client](-client/index.html)) : [AbstractAnimatedMapObject](../server.maps/-abstract-animated-map-object/index.html) |
| [CharacterNameAndId](-character-name-and-id/index.html) | [jvm]<br>open class [CharacterNameAndId](-character-name-and-id/index.html)(**id**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [CharacterStat](-character-stat/index.html) | [jvm]<br>enum [CharacterStat](-character-stat/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[CharacterStat](-character-stat/index.html)> |
| [Client](-client/index.html) | [jvm]<br>class [Client](-client/index.html)(**sendCrypto**: [MapleAESOFB](../tools/-maple-a-e-s-o-f-b/index.html), **receiveCrypto**: [MapleAESOFB](../tools/-maple-a-e-s-o-f-b/index.html), **session**: IoSession?) |
| [DCHandler](-d-c-handler/index.html) | [jvm]<br>class [DCHandler](-d-c-handler/index.html) : [AbstractPacketHandler](../net/-abstract-packet-handler/index.html) |
| [Disease](-disease/index.html) | [jvm]<br>enum [Disease](-disease/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Disease](-disease/index.html)> |
| [DiseaseValueHolder](-disease-value-holder/index.html) | [jvm]<br>data class [DiseaseValueHolder](-disease-value-holder/index.html)(**start**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **length**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [Job](-job/index.html) | [jvm]<br>enum [Job](-job/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Job](-job/index.html)> |
| [KeyBinding](-key-binding/index.html) | [jvm]<br>data class [KeyBinding](-key-binding/index.html)(**type**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **action**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [MonsterBook](-monster-book/index.html) | [jvm]<br>class [MonsterBook](-monster-book/index.html) |
| [Mount](-mount/index.html) | [jvm]<br>class [Mount](-mount/index.html)(**owner**: [Character](-character/index.html), **itemId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **skillId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [QuestStatus](-quest-status/index.html) | [jvm]<br>class [QuestStatus](-quest-status/index.html)(**quest**: [Quest](../server.quest/-quest/index.html), **status**: [QuestStatus.Status](-quest-status/-status/index.html), **npc**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [Ring](-ring/index.html) | [jvm]<br>class [Ring](-ring/index.html)(**ringId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **partnerRingId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **partnerId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **itemId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **partnerName**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Comparable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)<[Ring](-ring/index.html)> |
| [Skill](-skill/index.html) | [jvm]<br>class [Skill](-skill/index.html)(**id**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [SkillFactory](-skill-factory/index.html) | [jvm]<br>class [SkillFactory](-skill-factory/index.html) |

