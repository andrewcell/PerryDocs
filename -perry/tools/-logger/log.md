---
title: log
---
//[Perry](../../../index.html)/[tools](../index.html)/[Logger](index.html)/[log](log.html)



# log



[jvm]\




@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()



fun [log](log.html)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, className: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [Logger.Type](-type/index.html) = Type.NORMAL, stackTrace: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)>? = null)



Log message. To save to log file or print to console.



Example: <pre>Logger.log("message", "className", Type.NORMAL, null)</pre>



#### Author



Andrew M. Bray



## Parameters


jvm

| | |
|---|---|
| message | Main message to log. it could be Exception's message, or developer's personal message. |
| className | This will display as header. For determine where this message came from. |
| type | Type of Message. Warning or Critical will display additional type header in front of message. |
| stackTrace | Stacktrace from exception. default value is null, so it is optional. when stacktrace print options is enabled, stacktrace will appear in console or file. |





[jvm]\
fun [log](log.html)(e: [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html), className: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [Logger.Type](-type/index.html) = Type.CRITICAL)




