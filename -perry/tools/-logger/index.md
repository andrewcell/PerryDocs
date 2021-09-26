---
title: Logger
---
//[Perry](../../../index.html)/[tools](../index.html)/[Logger](index.html)



# Logger



[jvm]\
object [Logger](index.html)

Everything for Logging



#### Author



Andrew M. Bray



## Types


| Name | Summary |
|---|---|
| [Type](-type/index.html) | [jvm]<br>enum [Type](-type/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Logger.Type](-type/index.html)> |


## Functions


| Name | Summary |
|---|---|
| [log](log.html) | [jvm]<br>fun [log](log.html)(e: [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html), className: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [Logger.Type](-type/index.html) = Type.CRITICAL)<br>[jvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()<br>fun [log](log.html)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, className: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [Logger.Type](-type/index.html) = Type.NORMAL, stackTrace: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)>? = null)<br>Log message. |

