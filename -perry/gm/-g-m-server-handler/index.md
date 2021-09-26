---
title: GMServerHandler
---
//[Perry](../../../index.html)/[gm](../index.html)/[GMServerHandler](index.html)



# GMServerHandler



[jvm]\
class [GMServerHandler](index.html) : IoHandlerAdapter



## Functions


| Name | Summary |
|---|---|
| [event](../../net/-server-handler/index.html#-969487755%2FFunctions%2F863300109) | [jvm]<br>open override fun [event](../../net/-server-handler/index.html#-969487755%2FFunctions%2F863300109)(p0: IoSession, p1: FilterEvent) |
| [exceptionCaught](exception-caught.html) | [jvm]<br>open override fun [exceptionCaught](exception-caught.html)(session: IoSession?, cause: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?) |
| [inputClosed](../../net/-server-handler/index.html#-346250503%2FFunctions%2F863300109) | [jvm]<br>open override fun [inputClosed](../../net/-server-handler/index.html#-346250503%2FFunctions%2F863300109)(p0: IoSession) |
| [messageReceived](message-received.html) | [jvm]<br>open override fun [messageReceived](message-received.html)(session: IoSession?, message: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?) |
| [messageSent](../../net/-server-handler/index.html#-585887408%2FFunctions%2F863300109) | [jvm]<br>open override fun [messageSent](../../net/-server-handler/index.html#-585887408%2FFunctions%2F863300109)(p0: IoSession, p1: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) |
| [sessionClosed](session-closed.html) | [jvm]<br>open override fun [sessionClosed](session-closed.html)(session: IoSession?) |
| [sessionCreated](../../net/-server-handler/index.html#-197247531%2FFunctions%2F863300109) | [jvm]<br>open override fun [sessionCreated](../../net/-server-handler/index.html#-197247531%2FFunctions%2F863300109)(p0: IoSession) |
| [sessionIdle](session-idle.html) | [jvm]<br>open override fun [sessionIdle](session-idle.html)(session: IoSession?, status: IdleStatus?) |
| [sessionOpened](session-opened.html) | [jvm]<br>open override fun [sessionOpened](session-opened.html)(session: IoSession?) |


## Properties


| Name | Summary |
|---|---|
| [processor](processor.html) | [jvm]<br>val [processor](processor.html): [GMPacketProcessor](../-g-m-packet-processor/index.html) |
| [session](session.html) | [jvm]<br>var [session](session.html): IoSession? = null |

