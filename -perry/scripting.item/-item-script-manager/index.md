---
title: ItemScriptManager
---
//[Perry](../../../index.html)/[scripting.item](../index.html)/[ItemScriptManager](index.html)



# ItemScriptManager



[jvm]\
object [ItemScriptManager](index.html)



## Functions


| Name | Summary |
|---|---|
| [getItemScript](get-item-script.html) | [jvm]<br>fun [getItemScript](get-item-script.html)(c: [Client](../../client/-client/index.html), scriptName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [scriptExists](script-exists.html) | [jvm]<br>fun [scriptExists](script-exists.html)(scriptName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Properties


| Name | Summary |
|---|---|
| [scripts](scripts.html) | [jvm]<br>val [scripts](scripts.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Invocable](https://docs.oracle.com/javase/8/docs/api/javax/script/Invocable.html)&gt; |
| [sef](sef.html) | [jvm]<br>val [sef](sef.html): [ScriptEngineFactory](https://docs.oracle.com/javase/8/docs/api/javax/script/ScriptEngineFactory.html) |

