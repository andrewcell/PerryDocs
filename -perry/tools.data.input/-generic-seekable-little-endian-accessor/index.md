---
title: GenericSeekableLittleEndianAccessor
---
//[Perry](../../../index.html)/[tools.data.input](../index.html)/[GenericSeekableLittleEndianAccessor](index.html)



# GenericSeekableLittleEndianAccessor



[jvm]\
class [GenericSeekableLittleEndianAccessor](index.html)(bs: [SeekableInputStreamByteStream](../-seekable-input-stream-byte-stream/index.html)) : [GenericLittleEndianAccessor](../-generic-little-endian-accessor/index.html), [SeekableLittleEndianAccessor](../-seekable-little-endian-accessor/index.html)

Provides an abstract accessor to a generic Little Endian byte stream. This accessor is seekable.



## Constructors


| | |
|---|---|
| [GenericSeekableLittleEndianAccessor](-generic-seekable-little-endian-accessor.html) | [jvm]<br>fun [GenericSeekableLittleEndianAccessor](-generic-seekable-little-endian-accessor.html)(bs: [SeekableInputStreamByteStream](../-seekable-input-stream-byte-stream/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [available](../-generic-little-endian-accessor/available.html) | [jvm]<br>open override fun [available](../-generic-little-endian-accessor/available.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [read](../-generic-little-endian-accessor/read.html) | [jvm]<br>open override fun [read](../-generic-little-endian-accessor/read.html)(num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)<br>Reads <code>num</code> bytes off the stream. |
| [readASCIIString](../-generic-little-endian-accessor/read-a-s-c-i-i-string.html) | [jvm]<br>open override fun [readASCIIString](../-generic-little-endian-accessor/read-a-s-c-i-i-string.html)(n: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Reads an ASCII string from the stream with length <code>n</code>. |
| [readByte](../-generic-little-endian-accessor/read-byte.html) | [jvm]<br>open override fun [readByte](../-generic-little-endian-accessor/read-byte.html)(): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)<br>Read a single byte from the stream. |
| [readChar](../-generic-little-endian-accessor/read-char.html) | [jvm]<br>open override fun [readChar](../-generic-little-endian-accessor/read-char.html)(): [Char](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html)<br>Reads a single character from the stream. |
| [readDouble](../-generic-little-endian-accessor/read-double.html) | [jvm]<br>open override fun [readDouble](../-generic-little-endian-accessor/read-double.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Reads a double-precision integer from the stream. |
| [readFloat](../-generic-little-endian-accessor/read-float.html) | [jvm]<br>open override fun [readFloat](../-generic-little-endian-accessor/read-float.html)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Reads a floating point integer from the stream. |
| [readGameASCIIString](../-generic-little-endian-accessor/read-game-a-s-c-i-i-string.html) | [jvm]<br>open override fun [readGameASCIIString](../-generic-little-endian-accessor/read-game-a-s-c-i-i-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Reads a Client convention lengthed ASCII string. This consists of a short integer telling the length of the string, then the string itself. |
| [readInt](../-generic-little-endian-accessor/read-int.html) | [jvm]<br>open override fun [readInt](../-generic-little-endian-accessor/read-int.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Reads an integer from the stream. |
| [readLong](../-generic-little-endian-accessor/read-long.html) | [jvm]<br>open override fun [readLong](../-generic-little-endian-accessor/read-long.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Reads a long integer from the stream. |
| [readNullTerminatedASCIIString](../-generic-little-endian-accessor/read-null-terminated-a-s-c-i-i-string.html) | [jvm]<br>open override fun [readNullTerminatedASCIIString](../-generic-little-endian-accessor/read-null-terminated-a-s-c-i-i-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Reads a null-terminated string from the stream. |
| [readPos](../-generic-little-endian-accessor/read-pos.html) | [jvm]<br>open override fun [readPos](../-generic-little-endian-accessor/read-pos.html)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Reads a Client Position information. This consists of 2 short integer. |
| [readShort](../-generic-little-endian-accessor/read-short.html) | [jvm]<br>open override fun [readShort](../-generic-little-endian-accessor/read-short.html)(): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html)<br>Reads a short integer from the stream. |
| [seek](seek.html) | [jvm]<br>open override fun [seek](seek.html)(offset: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>Seek the pointer to <code>offset</code> |
| [skip](skip.html) | [jvm]<br>open override fun [skip](skip.html)(num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Skip <code>num</code> number of bytes in the stream. |
| [toString](../-generic-little-endian-accessor/to-string.html) | [jvm]<br>open override fun [toString](../-generic-little-endian-accessor/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |


## Properties


| Name | Summary |
|---|---|
| [bs](bs.html) | [jvm]<br>open override val [bs](bs.html): [SeekableInputStreamByteStream](../-seekable-input-stream-byte-stream/index.html) |
| [bytesRead](../-generic-little-endian-accessor/bytes-read.html) | [jvm]<br>open override val [bytesRead](../-generic-little-endian-accessor/bytes-read.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [position](position.html) | [jvm]<br>open override val [position](position.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |

