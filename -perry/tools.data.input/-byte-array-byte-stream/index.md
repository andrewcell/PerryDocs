---
title: ByteArrayByteStream
---
//[Perry](../../../index.html)/[tools.data.input](../index.html)/[ByteArrayByteStream](index.html)



# ByteArrayByteStream



[jvm]\
class [ByteArrayByteStream](index.html)(**array**: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)) : [SeekableInputStreamByteStream](../-seekable-input-stream-byte-stream/index.html)



## Functions


| Name | Summary |
|---|---|
| [available](available.html) | [jvm]<br>open override fun [available](available.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [readByte](read-byte.html) | [jvm]<br>open override fun [readByte](read-byte.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [seek](seek.html) | [jvm]<br>open override fun [seek](seek.html)(offset: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>Seeks the stream by the specified offset. |
| [toString](to-string.html) | [jvm]<br>open override fun [toString](to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |


## Properties


| Name | Summary |
|---|---|
| [array](array.html) | [jvm]<br>val [array](array.html): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [bytesRead](bytes-read.html) | [jvm]<br>open override var [bytesRead](bytes-read.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0L |
| [position](position.html) | [jvm]<br>open override var [position](position.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0<br>Current position of the stream. |

