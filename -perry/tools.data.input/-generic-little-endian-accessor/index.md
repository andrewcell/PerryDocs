---
title: GenericLittleEndianAccessor
---
//[Perry](../../../index.html)/[tools.data.input](../index.html)/[GenericLittleEndianAccessor](index.html)



# GenericLittleEndianAccessor



[jvm]\
open class [GenericLittleEndianAccessor](index.html)(bs: [ByteInputStream](../-byte-input-stream/index.html)) : [LittleEndianAccessor](../-little-endian-accessor/index.html)

Provides a generic interface to a Little Endian stream of bytes.



## Constructors


| | |
|---|---|
| [GenericLittleEndianAccessor](-generic-little-endian-accessor.html) | [jvm]<br>fun [GenericLittleEndianAccessor](-generic-little-endian-accessor.html)(bs: [ByteInputStream](../-byte-input-stream/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [available](available.html) | [jvm]<br>open override fun [available](available.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [read](read.html) | [jvm]<br>open override fun [read](read.html)(num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)<br>Reads <code>num</code> bytes off the stream. |
| [readASCIIString](read-a-s-c-i-i-string.html) | [jvm]<br>open override fun [readASCIIString](read-a-s-c-i-i-string.html)(n: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Reads an ASCII string from the stream with length <code>n</code>. |
| [readByte](read-byte.html) | [jvm]<br>open override fun [readByte](read-byte.html)(): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)<br>Read a single byte from the stream. |
| [readChar](read-char.html) | [jvm]<br>open override fun [readChar](read-char.html)(): [Char](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html)<br>Reads a single character from the stream. |
| [readDouble](read-double.html) | [jvm]<br>open override fun [readDouble](read-double.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Reads a double-precision integer from the stream. |
| [readFloat](read-float.html) | [jvm]<br>open override fun [readFloat](read-float.html)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Reads a floating point integer from the stream. |
| [readGameASCIIString](read-game-a-s-c-i-i-string.html) | [jvm]<br>open override fun [readGameASCIIString](read-game-a-s-c-i-i-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Reads a Client convention lengthed ASCII string. This consists of a short integer telling the length of the string, then the string itself. |
| [readInt](read-int.html) | [jvm]<br>open override fun [readInt](read-int.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Reads an integer from the stream. |
| [readLong](read-long.html) | [jvm]<br>open override fun [readLong](read-long.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Reads a long integer from the stream. |
| [readNullTerminatedASCIIString](read-null-terminated-a-s-c-i-i-string.html) | [jvm]<br>open override fun [readNullTerminatedASCIIString](read-null-terminated-a-s-c-i-i-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Reads a null-terminated string from the stream. |
| [readPos](read-pos.html) | [jvm]<br>open override fun [readPos](read-pos.html)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Reads a Client Position information. This consists of 2 short integer. |
| [readShort](read-short.html) | [jvm]<br>open override fun [readShort](read-short.html)(): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html)<br>Reads a short integer from the stream. |
| [skip](skip.html) | [jvm]<br>open override fun [skip](skip.html)(num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Skips the current position of the stream <code>num</code> bytes ahead. |
| [toString](to-string.html) | [jvm]<br>open override fun [toString](to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |


## Properties


| Name | Summary |
|---|---|
| [bs](bs.html) | [jvm]<br>open val [bs](bs.html): [ByteInputStream](../-byte-input-stream/index.html) |
| [bytesRead](bytes-read.html) | [jvm]<br>open override val [bytesRead](bytes-read.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |


## Inheritors


| Name |
|---|
| [GenericSeekableLittleEndianAccessor](../-generic-seekable-little-endian-accessor/index.html) |

