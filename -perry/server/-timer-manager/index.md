---
title: TimerManager
---
//[Perry](../../../index.html)/[server](../index.html)/[TimerManager](index.html)



# TimerManager



[jvm]\
object [TimerManager](index.html) : [TimerManagerMBean](../-timer-manager-m-bean/index.html)



## Functions


| Name | Summary |
|---|---|
| [isShutdown](is-shutdown.html) | [jvm]<br>open override fun [isShutdown](is-shutdown.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isTerminated](is-terminated.html) | [jvm]<br>open override fun [isTerminated](is-terminated.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [purge](purge.html) | [jvm]<br>fun [purge](purge.html)(): [Runnable](https://docs.oracle.com/javase/8/docs/api/java/lang/Runnable.html) |
| [register](register.html) | [jvm]<br>fun [register](register.html)(r: [Runnable](https://docs.oracle.com/javase/8/docs/api/java/lang/Runnable.html), repeatTime: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), delay: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? |
| [schedule](schedule.html) | [jvm]<br>fun [schedule](schedule.html)(r: [Runnable](https://docs.oracle.com/javase/8/docs/api/java/lang/Runnable.html), delay: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? |
| [scheduleAtTimestamp](schedule-at-timestamp.html) | [jvm]<br>fun [scheduleAtTimestamp](schedule-at-timestamp.html)(r: [Runnable](https://docs.oracle.com/javase/8/docs/api/java/lang/Runnable.html), timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? |
| [start](start.html) | [jvm]<br>fun [start](start.html)() |
| [stop](stop.html) | [jvm]<br>fun [stop](stop.html)() |


## Properties


| Name | Summary |
|---|---|
| [ses](ses.html) | [jvm]<br>var [ses](ses.html): [ScheduledThreadPoolExecutor](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledThreadPoolExecutor.html)? = null |

