---
title: Npc
---
//[Perry](../../../index.html)/[server.life](../index.html)/[Npc](index.html)



# Npc



[jvm]\
class [Npc](index.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), stats: [NpcStats](../-npc-stats/index.html)) : [AbstractLoadedLife](../../server.maps/-abstract-loaded-life/index.html)



## Functions


| Name | Summary |
|---|---|
| [hasShop](has-shop.html) | [jvm]<br>fun [hasShop](has-shop.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isFacingLeft](../../server.maps/-abstract-animated-map-object/is-facing-left.html) | [jvm]<br>open override fun [isFacingLeft](../../server.maps/-abstract-animated-map-object/is-facing-left.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [sendDestroyData](send-destroy-data.html) | [jvm]<br>open override fun [sendDestroyData](send-destroy-data.html)(client: [Client](../../client/-client/index.html)) |
| [sendShop](send-shop.html) | [jvm]<br>fun [sendShop](send-shop.html)(c: [Client](../../client/-client/index.html)): [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? |
| [sendSpawnData](send-spawn-data.html) | [jvm]<br>open override fun [sendSpawnData](send-spawn-data.html)(client: [Client](../../client/-client/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [cType](../../server.maps/-abstract-loaded-life/c-type.html) | [jvm]<br>var [cType](../../server.maps/-abstract-loaded-life/c-type.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [cy](../../server.maps/-abstract-loaded-life/cy.html) | [jvm]<br>var [cy](../../server.maps/-abstract-loaded-life/cy.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [f](../../server.maps/-abstract-loaded-life/f.html) | [jvm]<br>var [f](../../server.maps/-abstract-loaded-life/f.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [fh](../../server.maps/-abstract-loaded-life/fh.html) | [jvm]<br>var [fh](../../server.maps/-abstract-loaded-life/fh.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [hidden](../../server.maps/-abstract-loaded-life/hidden.html) | [jvm]<br>var [hidden](../../server.maps/-abstract-loaded-life/hidden.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [id](../../server.maps/-abstract-loaded-life/id.html) | [jvm]<br>val [id](../../server.maps/-abstract-loaded-life/id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [mTime](../../server.maps/-abstract-loaded-life/m-time.html) | [jvm]<br>var [mTime](../../server.maps/-abstract-loaded-life/m-time.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [objectId](../../server.maps/-abstract-map-object/object-id.html) | [jvm]<br>open override var [objectId](../../server.maps/-abstract-map-object/object-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [objectType](object-type.html) | [jvm]<br>open override val [objectType](object-type.html): [MapObjectType](../../server.maps/-map-object-type/index.html) |
| [position](../../server.maps/-abstract-map-object/position.html) | [jvm]<br>open override var [position](../../server.maps/-abstract-map-object/position.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [rx0](../../server.maps/-abstract-loaded-life/rx0.html) | [jvm]<br>var [rx0](../../server.maps/-abstract-loaded-life/rx0.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [rx1](../../server.maps/-abstract-loaded-life/rx1.html) | [jvm]<br>var [rx1](../../server.maps/-abstract-loaded-life/rx1.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [stance](../../server.maps/-abstract-animated-map-object/stance.html) | [jvm]<br>open override var [stance](../../server.maps/-abstract-animated-map-object/stance.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [startFh](../../server.maps/-abstract-loaded-life/start-fh.html) | [jvm]<br>var [startFh](../../server.maps/-abstract-loaded-life/start-fh.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [stats](stats.html) | [jvm]<br>val [stats](stats.html): [NpcStats](../-npc-stats/index.html) |

