---
title: NPCScriptManager
---
//[Perry](../../../index.html)/[scripting.npc](../index.html)/[NPCScriptManager](index.html)



# NPCScriptManager



[jvm]\
object [NPCScriptManager](index.html) : [AbstractScriptManager](../../scripting/-abstract-script-manager/index.html)



## Functions


| Name | Summary |
|---|---|
| [action](action.html) | [jvm]<br>fun [action](action.html)(c: [Client](../../client/-client/index.html), mode: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), type: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), selection: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [dispose](dispose.html) | [jvm]<br>fun [dispose](dispose.html)(c: [Client](../../client/-client/index.html))<br>fun [dispose](dispose.html)(cm: [NPCConversationManager](../-n-p-c-conversation-manager/index.html)) |
| [getCM](get-c-m.html) | [jvm]<br>fun [getCM](get-c-m.html)(c: [Client](../../client/-client/index.html)): [NPCConversationManager](../-n-p-c-conversation-manager/index.html)? |
| [getScriptFileReader](../../scripting/-abstract-script-manager/get-script-file-reader.html) | [jvm]<br>fun [getScriptFileReader](../../scripting/-abstract-script-manager/get-script-file-reader.html)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [FileReader](https://docs.oracle.com/javase/8/docs/api/java/io/FileReader.html)? |
| [notice](notice.html) | [jvm]<br>fun [notice](notice.html)(c: [Client](../../client/-client/index.html), id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? |
| [resetContext](../../scripting/-abstract-script-manager/reset-context.html) | [jvm]<br>fun [resetContext](../../scripting/-abstract-script-manager/reset-context.html)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), c: [Client](../../client/-client/index.html)): [ScriptEngine](https://docs.oracle.com/javase/8/docs/api/javax/script/ScriptEngine.html)? |
| [start](start.html) | [jvm]<br>fun [start](start.html)(c: [Client](../../client/-client/index.html), npc: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), filename: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, chr: [Character](../../client/-character/index.html)?) |


## Properties


| Name | Summary |
|---|---|
| [cms](cms.html) | [jvm]<br>val [cms](cms.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Client](../../client/-client/index.html), [NPCConversationManager](../-n-p-c-conversation-manager/index.html)&gt; |
| [scripts](scripts.html) | [jvm]<br>val [scripts](scripts.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Client](../../client/-client/index.html), [Invocable](https://docs.oracle.com/javase/8/docs/api/javax/script/Invocable.html)&gt; |

