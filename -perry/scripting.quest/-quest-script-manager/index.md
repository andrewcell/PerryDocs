---
title: QuestScriptManager
---
//[Perry](../../../index.html)/[scripting.quest](../index.html)/[QuestScriptManager](index.html)



# QuestScriptManager



[jvm]\
object [QuestScriptManager](index.html) : [AbstractScriptManager](../../scripting/-abstract-script-manager/index.html)



## Functions


| Name | Summary |
|---|---|
| [dispose](dispose.html) | [jvm]<br>fun [dispose](dispose.html)(c: [Client](../../client/-client/index.html))<br>fun [dispose](dispose.html)(qm: [QuestActionManager](../-quest-action-manager/index.html), c: [Client](../../client/-client/index.html)) |
| [end](end.html) | [jvm]<br>fun [end](end.html)(c: [Client](../../client/-client/index.html), questId: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), npc: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>fun [end](end.html)(c: [Client](../../client/-client/index.html), mode: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), type: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), selection: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [getQM](get-q-m.html) | [jvm]<br>fun [getQM](get-q-m.html)(c: [Client](../../client/-client/index.html)): [QuestActionManager](../-quest-action-manager/index.html)? |
| [getScriptFileReader](../../scripting/-abstract-script-manager/get-script-file-reader.html) | [jvm]<br>fun [getScriptFileReader](../../scripting/-abstract-script-manager/get-script-file-reader.html)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [FileReader](https://docs.oracle.com/javase/8/docs/api/java/io/FileReader.html)? |
| [resetContext](../../scripting/-abstract-script-manager/reset-context.html) | [jvm]<br>fun [resetContext](../../scripting/-abstract-script-manager/reset-context.html)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), c: [Client](../../client/-client/index.html)): [ScriptEngine](https://docs.oracle.com/javase/8/docs/api/javax/script/ScriptEngine.html)? |
| [start](start.html) | [jvm]<br>fun [start](start.html)(c: [Client](../../client/-client/index.html), questId: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), npc: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>fun [start](start.html)(c: [Client](../../client/-client/index.html), mode: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), type: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), selection: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [qms](qms.html) | [jvm]<br>val [qms](qms.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Client](../../client/-client/index.html), [QuestActionManager](../-quest-action-manager/index.html)&gt; |
| [scripts](scripts.html) | [jvm]<br>val [scripts](scripts.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Client](../../client/-client/index.html), [Invocable](https://docs.oracle.com/javase/8/docs/api/javax/script/Invocable.html)&gt; |

