---
title: PacketLittleEndianWriter
---
//[Perry](../../../index.html)/[tools.data.output](../index.html)/[PacketLittleEndianWriter](index.html)



# PacketLittleEndianWriter



[jvm]\
class [PacketLittleEndianWriter](index.html)(**size**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [GenericLittleEndianWriter](../-generic-little-endian-writer/index.html)

Writes a client-packet little-endian stream of bytes.



## Constructors


| | |
|---|---|
| [PacketLittleEndianWriter](-packet-little-endian-writer.html) | [jvm]<br>fun [PacketLittleEndianWriter](-packet-little-endian-writer.html)(size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 32) |


## Functions


| Name | Summary |
|---|---|
| [getPacket](get-packet.html) | [jvm]<br>fun [getPacket](get-packet.html)(): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [skip](../-generic-little-endian-writer/skip.html) | [jvm]<br>open override fun [skip](../-generic-little-endian-writer/skip.html)(b: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [write](../-generic-little-endian-writer/write.html) | [jvm]<br>open override fun [write](../-generic-little-endian-writer/write.html)(b: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html))<br>Write a byte to the stream.<br>[jvm]<br>open override fun [write](../-generic-little-endian-writer/write.html)(b: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html))<br>Write an array of bytes to the stream.<br>[jvm]<br>open override fun [write](../-generic-little-endian-writer/write.html)(b: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Write a byte in integer form to the stream. |
| [writeASCIIString](../-generic-little-endian-writer/write-a-s-c-i-i-string.html) | [jvm]<br>open override fun [writeASCIIString](../-generic-little-endian-writer/write-a-s-c-i-i-string.html)(s: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Writes an ASCII string the stream.<br>[jvm]<br>open override fun [writeASCIIString](../-generic-little-endian-writer/write-a-s-c-i-i-string.html)(s: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [writeBool](../-generic-little-endian-writer/write-bool.html) | [jvm]<br>open override fun [writeBool](../-generic-little-endian-writer/write-bool.html)(b: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Writes a boolean true ? |
| [writeGameASCIIString](../-generic-little-endian-writer/write-game-a-s-c-i-i-string.html) | [jvm]<br>open override fun [writeGameASCIIString](../-generic-little-endian-writer/write-game-a-s-c-i-i-string.html)(s: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Writes a maple-convention ASCII string to the stream. |
| [writeInt](../-generic-little-endian-writer/write-int.html) | [jvm]<br>open override fun [writeInt](../-generic-little-endian-writer/write-int.html)(i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Writes an integer to the stream. |
| [writeLong](../-generic-little-endian-writer/write-long.html) | [jvm]<br>open override fun [writeLong](../-generic-little-endian-writer/write-long.html)(l: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>Write a long integer to the stream. |
| [writeNullTerminatedASCIIString](../-generic-little-endian-writer/write-null-terminated-a-s-c-i-i-string.html) | [jvm]<br>open override fun [writeNullTerminatedASCIIString](../-generic-little-endian-writer/write-null-terminated-a-s-c-i-i-string.html)(s: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Writes a null-terminated ASCII string to the stream. |
| [writePos](../-generic-little-endian-writer/write-pos.html) | [jvm]<br>open override fun [writePos](../-generic-little-endian-writer/write-pos.html)(s: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>Writes a 2D 4 byte position information |
| [writeShort](../-generic-little-endian-writer/write-short.html) | [jvm]<br>open override fun [writeShort](../-generic-little-endian-writer/write-short.html)(s: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Write a short integer to the stream. |


## Properties


| Name | Summary |
|---|---|
| [baos](baos.html) | [jvm]<br>val [baos](baos.html): [ByteArrayOutputStream](https://docs.oracle.com/javase/8/docs/api/java/io/ByteArrayOutputStream.html) |
| [bos](index.html#-1728414467%2FProperties%2F863300109) | [jvm]<br>var [bos](index.html#-1728414467%2FProperties%2F863300109): [ByteOutputStream](../-byte-output-stream/index.html)? = null |
| [size](size.html) | [jvm]<br>val [size](size.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 32 |

