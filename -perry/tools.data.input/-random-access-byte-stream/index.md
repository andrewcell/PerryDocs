---
title: RandomAccessByteStream
---
//[Perry](../../../index.html)/[tools.data.input](../index.html)/[RandomAccessByteStream](index.html)



# RandomAccessByteStream



[jvm]\
class [RandomAccessByteStream](index.html)(raf: [RandomAccessFile](https://docs.oracle.com/javase/8/docs/api/java/io/RandomAccessFile.html)) : [SeekableInputStreamByteStream](../-seekable-input-stream-byte-stream/index.html)

Provides an abstract layer to a byte stream. This layer can be accessed randomly.



## Constructors


| | |
|---|---|
| [RandomAccessByteStream](-random-access-byte-stream.html) | [jvm]<br>fun [RandomAccessByteStream](-random-access-byte-stream.html)(raf: [RandomAccessFile](https://docs.oracle.com/javase/8/docs/api/java/io/RandomAccessFile.html)) |


## Functions


| Name | Summary |
|---|---|
| [available](available.html) | [jvm]<br>open override fun [available](available.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [readByte](read-byte.html) | [jvm]<br>open override fun [readByte](read-byte.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [seek](seek.html) | [jvm]<br>open override fun [seek](seek.html)(offset: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>Seeks the stream by the specified offset. |


## Properties


| Name | Summary |
|---|---|
| [bytesRead](bytes-read.html) | [jvm]<br>open override var [bytesRead](bytes-read.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0L |
| [position](position.html) | [jvm]<br>open override val [position](position.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Current position of the stream. |
| [raf](raf.html) | [jvm]<br>val [raf](raf.html): [RandomAccessFile](https://docs.oracle.com/javase/8/docs/api/java/io/RandomAccessFile.html) |

