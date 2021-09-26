---
title: MapScriptManager
---
//[Perry](../../../index.html)/[scripting.map](../index.html)/[MapScriptManager](index.html)



# MapScriptManager



[jvm]\
object [MapScriptManager](index.html)



## Functions


| Name | Summary |
|---|---|
| [getMapScript](get-map-script.html) | [jvm]<br>fun [getMapScript](get-map-script.html)(c: [Client](../../client/-client/index.html), scriptName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), firstUser: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [reloadScripts](reload-scripts.html) | [jvm]<br>fun [reloadScripts](reload-scripts.html)() |
| [scriptExists](script-exists.html) | [jvm]<br>fun [scriptExists](script-exists.html)(scriptName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), firstUser: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Properties


| Name | Summary |
|---|---|
| [scripts](scripts.html) | [jvm]<br>val [scripts](scripts.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Invocable](https://docs.oracle.com/javase/8/docs/api/javax/script/Invocable.html)> |
| [sef](sef.html) | [jvm]<br>val [sef](sef.html): [ScriptEngineFactory](https://docs.oracle.com/javase/8/docs/api/javax/script/ScriptEngineFactory.html) |

