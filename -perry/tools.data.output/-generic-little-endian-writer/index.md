---
title: GenericLittleEndianWriter
---
//[Perry](../../../index.html)/[tools.data.output](../index.html)/[GenericLittleEndianWriter](index.html)



# GenericLittleEndianWriter



[jvm]\
open class [GenericLittleEndianWriter](index.html) : [LittleEndianWriter](../-little-endian-writer/index.html)



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [skip](skip.html) | [jvm]<br>open override fun [skip](skip.html)(b: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [write](write.html) | [jvm]<br>open override fun [write](write.html)(b: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html))<br>Write a byte to the stream.<br>[jvm]<br>open override fun [write](write.html)(b: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html))<br>Write an array of bytes to the stream.<br>[jvm]<br>open override fun [write](write.html)(b: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Write a byte in integer form to the stream. |
| [writeASCIIString](write-a-s-c-i-i-string.html) | [jvm]<br>open override fun [writeASCIIString](write-a-s-c-i-i-string.html)(s: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Writes an ASCII string the stream.<br>[jvm]<br>open override fun [writeASCIIString](write-a-s-c-i-i-string.html)(s: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [writeBool](write-bool.html) | [jvm]<br>open override fun [writeBool](write-bool.html)(b: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Writes a boolean true ? 1 : 0 |
| [writeGameASCIIString](write-game-a-s-c-i-i-string.html) | [jvm]<br>open override fun [writeGameASCIIString](write-game-a-s-c-i-i-string.html)(s: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Writes a maple-convention ASCII string to the stream. |
| [writeInt](write-int.html) | [jvm]<br>open override fun [writeInt](write-int.html)(i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Writes an integer to the stream. |
| [writeLong](write-long.html) | [jvm]<br>open override fun [writeLong](write-long.html)(l: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>Write a long integer to the stream. |
| [writeNullTerminatedASCIIString](write-null-terminated-a-s-c-i-i-string.html) | [jvm]<br>open override fun [writeNullTerminatedASCIIString](write-null-terminated-a-s-c-i-i-string.html)(s: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Writes a null-terminated ASCII string to the stream. |
| [writePos](write-pos.html) | [jvm]<br>open override fun [writePos](write-pos.html)(s: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>Writes a 2D 4 byte position information |
| [writeShort](write-short.html) | [jvm]<br>open override fun [writeShort](write-short.html)(s: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Write a short integer to the stream. |


## Properties


| Name | Summary |
|---|---|
| [bos](bos.html) | [jvm]<br>var [bos](bos.html): [ByteOutputStream](../-byte-output-stream/index.html)? = null |


## Inheritors


| Name |
|---|
| [PacketLittleEndianWriter](../-packet-little-endian-writer/index.html) |

