---
title: Pyramid
---
//[Perry](../../../index.html)/[server.partyquest](../index.html)/[Pyramid](index.html)



# Pyramid



[jvm]\
class [Pyramid](index.html)(party: [Party](../../net.server.world/-party/index.html), mode: [Pyramid.PyramidMode](-pyramid-mode/index.html), mapId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [PartyQuest](../-party-quest/index.html)



## Types


| Name | Summary |
|---|---|
| [PyramidMode](-pyramid-mode/index.html) | [jvm]<br>enum [PyramidMode](-pyramid-mode/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[Pyramid.PyramidMode](-pyramid-mode/index.html)&gt; |


## Functions


| Name | Summary |
|---|---|
| [broadcastInfo](broadcast-info.html) | [jvm]<br>fun [broadcastInfo](broadcast-info.html)(info: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), amount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [checkBuffs](check-buffs.html) | [jvm]<br>fun [checkBuffs](check-buffs.html)() |
| [cool](cool.html) | [jvm]<br>fun [cool](cool.html)() |
| [kill](kill.html) | [jvm]<br>fun [kill](kill.html)() |
| [miss](miss.html) | [jvm]<br>fun [miss](miss.html)() |
| [removeParticipant](../-party-quest/remove-participant.html) | [jvm]<br>fun [removeParticipant](../-party-quest/remove-participant.html)(chr: [Character](../../client/-character/index.html)) |
| [sendScore](send-score.html) | [jvm]<br>fun [sendScore](send-score.html)(chr: [Character](../../client/-character/index.html)) |
| [startGaugeSchedule](start-gauge-schedule.html) | [jvm]<br>fun [startGaugeSchedule](start-gauge-schedule.html)() |
| [timer](timer.html) | [jvm]<br>fun [timer](timer.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [useSkill](use-skill.html) | [jvm]<br>fun [useSkill](use-skill.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [warp](warp.html) | [jvm]<br>fun [warp](warp.html)(mapId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [buffCount](buff-count.html) | [jvm]<br>var [buffCount](buff-count.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 0 |
| [channel](../-party-quest/channel.html) | [jvm]<br>val [channel](../-party-quest/channel.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [cool](cool.html) | [jvm]<br>var [cool](cool.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [coolAdd](cool-add.html) | [jvm]<br>var [coolAdd](cool-add.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 5 |
| [count](count.html) | [jvm]<br>var [count](count.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [decrease](decrease.html) | [jvm]<br>var [decrease](decrease.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 1 |
| [exp](exp.html) | [jvm]<br>var [exp](exp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [gauge](gauge.html) | [jvm]<br>var [gauge](gauge.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 100 |
| [gaugeSchedule](gauge-schedule.html) | [jvm]<br>var [gaugeSchedule](gauge-schedule.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)&lt;*&gt;? = null |
| [kill](kill.html) | [jvm]<br>var [kill](kill.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [map](map.html) | [jvm]<br>var [map](map.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [mapId](map-id.html) | [jvm]<br>val [mapId](map-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [miss](miss.html) | [jvm]<br>var [miss](miss.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [missSub](miss-sub.html) | [jvm]<br>var [missSub](miss-sub.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 4 |
| [mode](mode.html) | [jvm]<br>val [mode](mode.html): [Pyramid.PyramidMode](-pyramid-mode/index.html) |
| [participants](../-party-quest/participants.html) | [jvm]<br>val [participants](../-party-quest/participants.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Character](../../client/-character/index.html)&gt; |
| [party](../-party-quest/party.html) | [jvm]<br>val [party](../-party-quest/party.html): [Party](../../net.server.world/-party/index.html) |
| [rank](rank.html) | [jvm]<br>var [rank](rank.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 0 |
| [skill](skill.html) | [jvm]<br>var [skill](skill.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 0 |
| [stage](stage.html) | [jvm]<br>var [stage](stage.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 0 |
| [timer](timer.html) | [jvm]<br>var [timer](timer.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)&lt;*&gt;? = null |
| [world](../-party-quest/world.html) | [jvm]<br>val [world](../-party-quest/world.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

