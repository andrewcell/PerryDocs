---
title: ServerHandler
---
//[Perry](../../../index.html)/[net](../index.html)/[ServerHandler](index.html)



# ServerHandler



[jvm]\
class [ServerHandler](index.html)(world: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), channel: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : IoHandlerAdapter



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [event](index.html#-969487755%2FFunctions%2F863300109) | [jvm]<br>open override fun [event](index.html#-969487755%2FFunctions%2F863300109)(p0: IoSession, p1: FilterEvent) |
| [exceptionCaught](exception-caught.html) | [jvm]<br>open override fun [exceptionCaught](exception-caught.html)(session: IoSession?, cause: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?) |
| [inputClosed](index.html#-346250503%2FFunctions%2F863300109) | [jvm]<br>open override fun [inputClosed](index.html#-346250503%2FFunctions%2F863300109)(p0: IoSession) |
| [messageReceived](message-received.html) | [jvm]<br>open override fun [messageReceived](message-received.html)(session: IoSession?, message: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?) |
| [messageSent](index.html#-585887408%2FFunctions%2F863300109) | [jvm]<br>open override fun [messageSent](index.html#-585887408%2FFunctions%2F863300109)(p0: IoSession, p1: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) |
| [sessionClosed](session-closed.html) | [jvm]<br>open override fun [sessionClosed](session-closed.html)(session: IoSession?) |
| [sessionCreated](index.html#-197247531%2FFunctions%2F863300109) | [jvm]<br>open override fun [sessionCreated](index.html#-197247531%2FFunctions%2F863300109)(p0: IoSession) |
| [sessionIdle](session-idle.html) | [jvm]<br>open override fun [sessionIdle](session-idle.html)(session: IoSession?, status: IdleStatus?) |
| [sessionOpened](session-opened.html) | [jvm]<br>open override fun [sessionOpened](session-opened.html)(session: IoSession?) |


## Properties


| Name | Summary |
|---|---|
| [channel](channel.html) | [jvm]<br>val [channel](channel.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [processor](processor.html) | [jvm]<br>val [processor](processor.html): [PacketProcessor](../-packet-processor/index.html) |
| [world](world.html) | [jvm]<br>val [world](world.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

