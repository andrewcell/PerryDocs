---
title: Mist
---
//[Perry](../../../index.html)/[server.maps](../index.html)/[Mist](index.html)



# Mist



[jvm]\
class [Mist](index.html)(mistPosition: [Rectangle](https://docs.oracle.com/javase/8/docs/api/java/awt/Rectangle.html)) : [AbstractMapObject](../-abstract-map-object/index.html)



## Constructors


| | |
|---|---|
| [Mist](-mist.html) | [jvm]<br>fun [Mist](-mist.html)(mistPosition: [Rectangle](https://docs.oracle.com/javase/8/docs/api/java/awt/Rectangle.html), mob: [Monster](../../server.life/-monster/index.html), skill: [MobSkill](../../server.life/-mob-skill/index.html)) |
| [Mist](-mist.html) | [jvm]<br>fun [Mist](-mist.html)(mistPosition: [Rectangle](https://docs.oracle.com/javase/8/docs/api/java/awt/Rectangle.html), owner: [Character](../../client/-character/index.html), source: [StatEffect](../../server/-stat-effect/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [getSourceSkill](get-source-skill.html) | [jvm]<br>fun [getSourceSkill](get-source-skill.html)(): [Skill](../../client/-skill/index.html)? |
| [makeChanceResult](make-chance-result.html) | [jvm]<br>fun [makeChanceResult](make-chance-result.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [makeDestroyData](make-destroy-data.html) | [jvm]<br>fun [makeDestroyData](make-destroy-data.html)(): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [makeFakeSpawnData](make-fake-spawn-data.html) | [jvm]<br>fun [makeFakeSpawnData](make-fake-spawn-data.html)(level: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [makeSpawnData](make-spawn-data.html) | [jvm]<br>fun [makeSpawnData](make-spawn-data.html)(): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [sendDestroyData](send-destroy-data.html) | [jvm]<br>open override fun [sendDestroyData](send-destroy-data.html)(client: [Client](../../client/-client/index.html)) |
| [sendSpawnData](send-spawn-data.html) | [jvm]<br>open override fun [sendSpawnData](send-spawn-data.html)(client: [Client](../../client/-client/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [isMobMist](is-mob-mist.html) | [jvm]<br>var [isMobMist](is-mob-mist.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [isPoisonMist](is-poison-mist.html) | [jvm]<br>var [isPoisonMist](is-poison-mist.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [mistPosition](mist-position.html) | [jvm]<br>val [mistPosition](mist-position.html): [Rectangle](https://docs.oracle.com/javase/8/docs/api/java/awt/Rectangle.html) |
| [mob](mob.html) | [jvm]<br>var [mob](mob.html): [Monster](../../server.life/-monster/index.html)? = null |
| [objectId](../-abstract-map-object/object-id.html) | [jvm]<br>open override var [objectId](../-abstract-map-object/object-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [objectType](object-type.html) | [jvm]<br>open override val [objectType](object-type.html): [MapObjectType](../-map-object-type/index.html) |
| [owner](owner.html) | [jvm]<br>var [owner](owner.html): [Character](../../client/-character/index.html)? = null |
| [position](position.html) | [jvm]<br>open override var [position](position.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [skill](skill.html) | [jvm]<br>var [skill](skill.html): [MobSkill](../../server.life/-mob-skill/index.html)? = null |
| [skillDelay](skill-delay.html) | [jvm]<br>var [skillDelay](skill-delay.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [source](source.html) | [jvm]<br>var [source](source.html): [StatEffect](../../server/-stat-effect/index.html)? = null |

