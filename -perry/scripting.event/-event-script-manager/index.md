---
title: EventScriptManager
---
//[Perry](../../../index.html)/[scripting.event](../index.html)/[EventScriptManager](index.html)



# EventScriptManager



[jvm]\
class [EventScriptManager](index.html)(**channelServer**: [Channel](../../net.server.channel/-channel/index.html), **scripts**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>) : [AbstractScriptManager](../../scripting/-abstract-script-manager/index.html)



## Types


| Name | Summary |
|---|---|
| [EventEntry](-event-entry/index.html) | [jvm]<br>data class [EventEntry](-event-entry/index.html)(**iv**: [Invocable](https://docs.oracle.com/javase/8/docs/api/javax/script/Invocable.html), **em**: [EventManager](../-event-manager/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [cancel](cancel.html) | [jvm]<br>fun [cancel](cancel.html)() |
| [getEventManager](get-event-manager.html) | [jvm]<br>fun [getEventManager](get-event-manager.html)(event: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [EventManager](../-event-manager/index.html)? |
| [getScriptFileReader](../../scripting/-abstract-script-manager/get-script-file-reader.html) | [jvm]<br>fun [getScriptFileReader](../../scripting/-abstract-script-manager/get-script-file-reader.html)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [FileReader](https://docs.oracle.com/javase/8/docs/api/java/io/FileReader.html)? |
| [init](init.html) | [jvm]<br>fun [init](init.html)() |
| [resetContext](../../scripting/-abstract-script-manager/reset-context.html) | [jvm]<br>fun [resetContext](../../scripting/-abstract-script-manager/reset-context.html)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), c: [Client](../../client/-client/index.html)): [ScriptEngine](https://docs.oracle.com/javase/8/docs/api/javax/script/ScriptEngine.html)? |


## Properties


| Name | Summary |
|---|---|
| [events](events.html) | [jvm]<br>val [events](events.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [EventScriptManager.EventEntry](-event-entry/index.html)> |

