---
title: PortalScriptManager
---
//[Perry](../../../index.html)/[scripting.portal](../index.html)/[PortalScriptManager](index.html)



# PortalScriptManager



[jvm]\
object [PortalScriptManager](index.html)



## Functions


| Name | Summary |
|---|---|
| [executePortalScript](execute-portal-script.html) | [jvm]<br>fun [executePortalScript](execute-portal-script.html)(portal: [Portal](../../server/-portal/index.html), c: [Client](../../client/-client/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getPortalScript](get-portal-script.html) | [jvm]<br>fun [getPortalScript](get-portal-script.html)(scriptName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [PortalScript](../-portal-script/index.html)? |
| [reloadPortalScripts](reload-portal-scripts.html) | [jvm]<br>fun [reloadPortalScripts](reload-portal-scripts.html)() |


## Properties


| Name | Summary |
|---|---|
| [scripts](scripts.html) | [jvm]<br>val [scripts](scripts.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [PortalScript](../-portal-script/index.html)?> |
| [sef](sef.html) | [jvm]<br>val [sef](sef.html): [ScriptEngineFactory](https://docs.oracle.com/javase/8/docs/api/javax/script/ScriptEngineFactory.html) |

