---
title: LittleEndianAccessor
---
//[Perry](../../../index.html)/[tools.data.input](../index.html)/[LittleEndianAccessor](index.html)



# LittleEndianAccessor



[jvm]\
interface [LittleEndianAccessor](index.html)



## Functions


| Name | Summary |
|---|---|
| [available](available.html) | [jvm]<br>abstract fun [available](available.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [read](read.html) | [jvm]<br>abstract fun [read](read.html)(num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [readASCIIString](read-a-s-c-i-i-string.html) | [jvm]<br>abstract fun [readASCIIString](read-a-s-c-i-i-string.html)(n: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [readByte](read-byte.html) | [jvm]<br>abstract fun [readByte](read-byte.html)(): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [readChar](read-char.html) | [jvm]<br>abstract fun [readChar](read-char.html)(): [Char](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html) |
| [readDouble](read-double.html) | [jvm]<br>abstract fun [readDouble](read-double.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [readFloat](read-float.html) | [jvm]<br>abstract fun [readFloat](read-float.html)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [readGameASCIIString](read-game-a-s-c-i-i-string.html) | [jvm]<br>abstract fun [readGameASCIIString](read-game-a-s-c-i-i-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [readInt](read-int.html) | [jvm]<br>abstract fun [readInt](read-int.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [readLong](read-long.html) | [jvm]<br>abstract fun [readLong](read-long.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [readNullTerminatedASCIIString](read-null-terminated-a-s-c-i-i-string.html) | [jvm]<br>abstract fun [readNullTerminatedASCIIString](read-null-terminated-a-s-c-i-i-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [readPos](read-pos.html) | [jvm]<br>abstract fun [readPos](read-pos.html)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [readShort](read-short.html) | [jvm]<br>abstract fun [readShort](read-short.html)(): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [skip](skip.html) | [jvm]<br>abstract fun [skip](skip.html)(num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [bytesRead](bytes-read.html) | [jvm]<br>abstract val [bytesRead](bytes-read.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |


## Inheritors


| Name |
|---|
| [GenericLittleEndianAccessor](../-generic-little-endian-accessor/index.html) |
| [SeekableLittleEndianAccessor](../-seekable-little-endian-accessor/index.html) |

