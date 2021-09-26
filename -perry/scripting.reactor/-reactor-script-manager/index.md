---
title: ReactorScriptManager
---
//[Perry](../../../index.html)/[scripting.reactor](../index.html)/[ReactorScriptManager](index.html)



# ReactorScriptManager



[jvm]\
object [ReactorScriptManager](index.html) : [AbstractScriptManager](../../scripting/-abstract-script-manager/index.html)



## Functions


| Name | Summary |
|---|---|
| [act](act.html) | [jvm]<br>fun [act](act.html)(c: [Client](../../client/-client/index.html), reactor: [Reactor](../../server.maps/-reactor/index.html)) |
| [getDrops](get-drops.html) | [jvm]<br>fun [getDrops](get-drops.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[ReactorDropEntry](../../server.maps/-reactor-drop-entry/index.html)&gt; |
| [getScriptFileReader](../../scripting/-abstract-script-manager/get-script-file-reader.html) | [jvm]<br>fun [getScriptFileReader](../../scripting/-abstract-script-manager/get-script-file-reader.html)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [FileReader](https://docs.oracle.com/javase/8/docs/api/java/io/FileReader.html)? |
| [resetContext](../../scripting/-abstract-script-manager/reset-context.html) | [jvm]<br>fun [resetContext](../../scripting/-abstract-script-manager/reset-context.html)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), c: [Client](../../client/-client/index.html)): [ScriptEngine](https://docs.oracle.com/javase/8/docs/api/javax/script/ScriptEngine.html)? |
| [touch](touch.html) | [jvm]<br>fun [touch](touch.html)(c: [Client](../../client/-client/index.html), reactor: [Reactor](../../server.maps/-reactor/index.html)) |
| [touching](touching.html) | [jvm]<br>fun [touching](touching.html)(c: [Client](../../client/-client/index.html), reactor: [Reactor](../../server.maps/-reactor/index.html), touching: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [untouch](untouch.html) | [jvm]<br>fun [untouch](untouch.html)(c: [Client](../../client/-client/index.html), reactor: [Reactor](../../server.maps/-reactor/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [drops](drops.html) | [jvm]<br>val [drops](drops.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[ReactorDropEntry](../../server.maps/-reactor-drop-entry/index.html)&gt;&gt; |

