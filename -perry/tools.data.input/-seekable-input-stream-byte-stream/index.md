---
title: SeekableInputStreamByteStream
---
//[Perry](../../../index.html)/[tools.data.input](../index.html)/[SeekableInputStreamByteStream](index.html)



# SeekableInputStreamByteStream



[jvm]\
interface [SeekableInputStreamByteStream](index.html) : [ByteInputStream](../-byte-input-stream/index.html)

Provides an abstract interface to a stream of bytes. This stream can be seeked.



## Functions


| Name | Summary |
|---|---|
| [available](../-byte-input-stream/available.html) | [jvm]<br>abstract fun [available](../-byte-input-stream/available.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [readByte](../-byte-input-stream/read-byte.html) | [jvm]<br>abstract fun [readByte](../-byte-input-stream/read-byte.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [seek](seek.html) | [jvm]<br>abstract fun [seek](seek.html)(offset: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>Seeks the stream by the specified offset. |


## Properties


| Name | Summary |
|---|---|
| [bytesRead](index.html#1214205473%2FProperties%2F863300109) | [jvm]<br>abstract val [bytesRead](index.html#1214205473%2FProperties%2F863300109): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [position](position.html) | [jvm]<br>abstract val [position](position.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Current position of the stream. |


## Inheritors


| Name |
|---|
| [ByteArrayByteStream](../-byte-array-byte-stream/index.html) |
| [RandomAccessByteStream](../-random-access-byte-stream/index.html) |

