---
title: InputStreamByteStream
---
//[Perry](../../../index.html)/[tools.data.input](../index.html)/[InputStreamByteStream](index.html)



# InputStreamByteStream



[jvm]\
class [InputStreamByteStream](index.html)(stream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html)) : [ByteInputStream](../-byte-input-stream/index.html)

Provides an abstract wrapper to a stream of bytes.



## Constructors


| | |
|---|---|
| [InputStreamByteStream](-input-stream-byte-stream.html) | [jvm]<br>fun [InputStreamByteStream](-input-stream-byte-stream.html)(stream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html)) |


## Functions


| Name | Summary |
|---|---|
| [available](available.html) | [jvm]<br>open override fun [available](available.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [readByte](read-byte.html) | [jvm]<br>open override fun [readByte](read-byte.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Reads the next byte from the stream. |


## Properties


| Name | Summary |
|---|---|
| [bytesRead](bytes-read.html) | [jvm]<br>open override var [bytesRead](bytes-read.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0L |
| [stream](stream.html) | [jvm]<br>val [stream](stream.html): [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html) |

