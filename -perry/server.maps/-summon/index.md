---
title: Summon
---
//[Perry](../../../index.html)/[server.maps](../index.html)/[Summon](index.html)



# Summon



[jvm]\
class [Summon](index.html)(owner: [Character](../../client/-character/index.html), skill: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), pos: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), movementType: [SummonMovementType](../-summon-movement-type/index.html)) : [AbstractAnimatedMapObject](../-abstract-animated-map-object/index.html)



## Functions


| Name | Summary |
|---|---|
| [addHp](add-hp.html) | [jvm]<br>fun [addHp](add-hp.html)(value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [isFacingLeft](../-abstract-animated-map-object/is-facing-left.html) | [jvm]<br>open override fun [isFacingLeft](../-abstract-animated-map-object/is-facing-left.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isPuppet](is-puppet.html) | [jvm]<br>fun [isPuppet](is-puppet.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isStationary](is-stationary.html) | [jvm]<br>fun [isStationary](is-stationary.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [sendDestroyData](send-destroy-data.html) | [jvm]<br>open override fun [sendDestroyData](send-destroy-data.html)(client: [Client](../../client/-client/index.html)) |
| [sendSpawnData](send-spawn-data.html) | [jvm]<br>open override fun [sendSpawnData](send-spawn-data.html)(client: [Client](../../client/-client/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [hp](hp.html) | [jvm]<br>var [hp](hp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [movementType](movement-type.html) | [jvm]<br>val [movementType](movement-type.html): [SummonMovementType](../-summon-movement-type/index.html) |
| [objectId](../-abstract-map-object/object-id.html) | [jvm]<br>open override var [objectId](../-abstract-map-object/object-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [objectType](object-type.html) | [jvm]<br>open override val [objectType](object-type.html): [MapObjectType](../-map-object-type/index.html) |
| [owner](owner.html) | [jvm]<br>val [owner](owner.html): [Character](../../client/-character/index.html) |
| [position](../-abstract-map-object/position.html) | [jvm]<br>open override var [position](../-abstract-map-object/position.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [skill](skill.html) | [jvm]<br>val [skill](skill.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [skillLevel](skill-level.html) | [jvm]<br>val [skillLevel](skill-level.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [stance](../-abstract-animated-map-object/stance.html) | [jvm]<br>open override var [stance](../-abstract-animated-map-object/stance.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |

