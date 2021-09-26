---
title: EventInstanceManager
---
//[Perry](../../../index.html)/[scripting.event](../index.html)/[EventInstanceManager](index.html)



# EventInstanceManager



[jvm]\
class [EventInstanceManager](index.html)(em: [EventManager](../-event-manager/index.html), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))



## Functions


| Name | Summary |
|---|---|
| [disbandParty](disband-party.html) | [jvm]<br>fun [disbandParty](disband-party.html)() |
| [dispose](dispose.html) | [jvm]<br>fun [dispose](dispose.html)() |
| [finishPQ](finish-p-q.html) | [jvm]<br>fun [finishPQ](finish-p-q.html)() |
| [getKillCount](get-kill-count.html) | [jvm]<br>fun [getKillCount](get-kill-count.html)(chr: [Character](../../client/-character/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMapInstance](get-map-instance.html) | [jvm]<br>fun [getMapInstance](get-map-instance.html)(mapId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [GameMap](../../server.maps/-game-map/index.html) |
| [getPlayerCount](get-player-count.html) | [jvm]<br>fun [getPlayerCount](get-player-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getPlayers](get-players.html) | [jvm]<br>fun [getPlayers](get-players.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Character](../../client/-character/index.html)&gt; |
| [getProperty](get-property.html) | [jvm]<br>fun [getProperty](get-property.html)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getTimeLeft](get-time-left.html) | [jvm]<br>fun [getTimeLeft](get-time-left.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [isLeader](is-leader.html) | [jvm]<br>fun [isLeader](is-leader.html)(chr: [Character](../../client/-character/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isTimerStarted](is-timer-started.html) | [jvm]<br>fun [isTimerStarted](is-timer-started.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [leftParty](left-party.html) | [jvm]<br>fun [leftParty](left-party.html)(chr: [Character](../../client/-character/index.html)) |
| [monsterKilled](monster-killed.html) | [jvm]<br>fun [monsterKilled](monster-killed.html)(chr: [Character](../../client/-character/index.html), mob: [Monster](../../server.life/-monster/index.html)) |
| [playerDisconnected](player-disconnected.html) | [jvm]<br>fun [playerDisconnected](player-disconnected.html)(chr: [Character](../../client/-character/index.html)) |
| [playerKilled](player-killed.html) | [jvm]<br>fun [playerKilled](player-killed.html)(chr: [Character](../../client/-character/index.html)) |
| [registerMonster](register-monster.html) | [jvm]<br>fun [registerMonster](register-monster.html)(mob: [Monster](../../server.life/-monster/index.html)) |
| [registerParty](register-party.html) | [jvm]<br>fun [registerParty](register-party.html)(party: [Party](../../net.server.world/-party/index.html), map: [GameMap](../../server.maps/-game-map/index.html)) |
| [registerPlayer](register-player.html) | [jvm]<br>fun [registerPlayer](register-player.html)(chr: [Character](../../client/-character/index.html)) |
| [removePlayer](remove-player.html) | [jvm]<br>fun [removePlayer](remove-player.html)(chr: [Character](../../client/-character/index.html)) |
| [revivePlayer](revive-player.html) | [jvm]<br>fun [revivePlayer](revive-player.html)(chr: [Character](../../client/-character/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [saveWinner](save-winner.html) | [jvm]<br>fun [saveWinner](save-winner.html)(chr: [Character](../../client/-character/index.html)) |
| [schedule](schedule.html) | [jvm]<br>fun [schedule](schedule.html)(methodName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), delay: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [setProperty](set-property.html) | [jvm]<br>fun [setProperty](set-property.html)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [startEventTimer](start-event-timer.html) | [jvm]<br>fun [startEventTimer](start-event-timer.html)(time: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [unregisterMonster](unregister-monster.html) | [jvm]<br>fun [unregisterMonster](unregister-monster.html)(mob: [Monster](../../server.life/-monster/index.html)) |
| [unregisterPlayer](unregister-player.html) | [jvm]<br>fun [unregisterPlayer](unregister-player.html)(chr: [Character](../../client/-character/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [chars](chars.html) | [jvm]<br>val [chars](chars.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Character](../../client/-character/index.html)&gt; |
| [em](em.html) | [jvm]<br>val [em](em.html): [EventManager](../-event-manager/index.html) |
| [eventTime](event-time.html) | [jvm]<br>var [eventTime](event-time.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0L |
| [killCount](kill-count.html) | [jvm]<br>val [killCount](kill-count.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Character](../../client/-character/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt; |
| [mapFactory](map-factory.html) | [jvm]<br>val [mapFactory](map-factory.html): [MapFactory](../../server.maps/-map-factory/index.html) |
| [mobs](mobs.html) | [jvm]<br>val [mobs](mobs.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Monster](../../server.life/-monster/index.html)&gt; |
| [name](name.html) | [jvm]<br>val [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [props](props.html) | [jvm]<br>val [props](props.html): [Properties](https://docs.oracle.com/javase/8/docs/api/java/util/Properties.html) |
| [timeStarted](time-started.html) | [jvm]<br>var [timeStarted](time-started.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0L |

