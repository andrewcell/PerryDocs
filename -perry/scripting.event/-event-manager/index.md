---
title: EventManager
---
//[Perry](../../../index.html)/[scripting.event](../index.html)/[EventManager](index.html)



# EventManager



[jvm]\
class [EventManager](index.html)(channelServer: [Channel](../../net.server.channel/-channel/index.html), iv: [Invocable](https://docs.oracle.com/javase/8/docs/api/javax/script/Invocable.html), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))



## Functions


| Name | Summary |
|---|---|
| [broadcastShip](broadcast-ship.html) | [jvm]<br>fun [broadcastShip](broadcast-ship.html)(mapId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), type: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [cancel](cancel.html) | [jvm]<br>fun [cancel](cancel.html)() |
| [cancelSchedule](cancel-schedule.html) | [jvm]<br>fun [cancelSchedule](cancel-schedule.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? |
| [disposeInstance](dispose-instance.html) | [jvm]<br>fun [disposeInstance](dispose-instance.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [EventInstanceManager](../-event-instance-manager/index.html)? |
| [getInstance](get-instance.html) | [jvm]<br>fun [getInstance](get-instance.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [EventInstanceManager](../-event-instance-manager/index.html)? |
| [getMapFactory](get-map-factory.html) | [jvm]<br>fun [getMapFactory](get-map-factory.html)(): [MapFactory](../../server.maps/-map-factory/index.html) |
| [newInstance](new-instance.html) | [jvm]<br>fun [newInstance](new-instance.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [EventInstanceManager](../-event-instance-manager/index.html) |
| [schedule](schedule.html) | [jvm]<br>fun [schedule](schedule.html)(methodName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), delay: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), eim: [EventInstanceManager](../-event-instance-manager/index.html)? = null) |
| [scheduleAtTimestamp](schedule-at-timestamp.html) | [jvm]<br>fun [scheduleAtTimestamp](schedule-at-timestamp.html)(methodName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)&lt;*&gt;? |
| [startInstance](start-instance.html) | [jvm]<br>fun [startInstance](start-instance.html)(party: [Party](../../net.server.world/-party/index.html), map: [GameMap](../../server.maps/-game-map/index.html))<br>fun [startInstance](start-instance.html)(eim: [EventInstanceManager](../-event-instance-manager/index.html), leader: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [warpAllPlayer](warp-all-player.html) | [jvm]<br>fun [warpAllPlayer](warp-all-player.html)(from: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), to: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [channelServer](channel-server.html) | [jvm]<br>val [channelServer](channel-server.html): [Channel](../../net.server.channel/-channel/index.html) |
| [instances](instances.html) | [jvm]<br>val [instances](instances.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [EventInstanceManager](../-event-instance-manager/index.html)&gt; |
| [iv](iv.html) | [jvm]<br>val [iv](iv.html): [Invocable](https://docs.oracle.com/javase/8/docs/api/javax/script/Invocable.html) |
| [name](name.html) | [jvm]<br>val [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [schedule](schedule.html) | [jvm]<br>var [schedule](schedule.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)&lt;*&gt;? = null |
| [shuffleReactors](shuffle-reactors.html) | [jvm]<br>var [shuffleReactors](shuffle-reactors.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |

