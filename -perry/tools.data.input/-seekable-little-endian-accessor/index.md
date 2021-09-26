---
title: SeekableLittleEndianAccessor
---
//[Perry](../../../index.html)/[tools.data.input](../index.html)/[SeekableLittleEndianAccessor](index.html)



# SeekableLittleEndianAccessor



[jvm]\
interface [SeekableLittleEndianAccessor](index.html) : [LittleEndianAccessor](../-little-endian-accessor/index.html)



## Functions


| Name | Summary |
|---|---|
| [available](../-little-endian-accessor/available.html) | [jvm]<br>abstract fun [available](../-little-endian-accessor/available.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [read](../-little-endian-accessor/read.html) | [jvm]<br>abstract fun [read](../-little-endian-accessor/read.html)(num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [readASCIIString](../-little-endian-accessor/read-a-s-c-i-i-string.html) | [jvm]<br>abstract fun [readASCIIString](../-little-endian-accessor/read-a-s-c-i-i-string.html)(n: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [readByte](../-little-endian-accessor/read-byte.html) | [jvm]<br>abstract fun [readByte](../-little-endian-accessor/read-byte.html)(): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [readChar](../-little-endian-accessor/read-char.html) | [jvm]<br>abstract fun [readChar](../-little-endian-accessor/read-char.html)(): [Char](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html) |
| [readDouble](../-little-endian-accessor/read-double.html) | [jvm]<br>abstract fun [readDouble](../-little-endian-accessor/read-double.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [readFloat](../-little-endian-accessor/read-float.html) | [jvm]<br>abstract fun [readFloat](../-little-endian-accessor/read-float.html)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [readGameASCIIString](../-little-endian-accessor/read-game-a-s-c-i-i-string.html) | [jvm]<br>abstract fun [readGameASCIIString](../-little-endian-accessor/read-game-a-s-c-i-i-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [readInt](../-little-endian-accessor/read-int.html) | [jvm]<br>abstract fun [readInt](../-little-endian-accessor/read-int.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [readLong](../-little-endian-accessor/read-long.html) | [jvm]<br>abstract fun [readLong](../-little-endian-accessor/read-long.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [readNullTerminatedASCIIString](../-little-endian-accessor/read-null-terminated-a-s-c-i-i-string.html) | [jvm]<br>abstract fun [readNullTerminatedASCIIString](../-little-endian-accessor/read-null-terminated-a-s-c-i-i-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [readPos](../-little-endian-accessor/read-pos.html) | [jvm]<br>abstract fun [readPos](../-little-endian-accessor/read-pos.html)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [readShort](../-little-endian-accessor/read-short.html) | [jvm]<br>abstract fun [readShort](../-little-endian-accessor/read-short.html)(): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [seek](seek.html) | [jvm]<br>abstract fun [seek](seek.html)(offset: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [skip](../-little-endian-accessor/skip.html) | [jvm]<br>abstract fun [skip](../-little-endian-accessor/skip.html)(num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [bytesRead](index.html#736111659%2FProperties%2F863300109) | [jvm]<br>abstract val [bytesRead](index.html#736111659%2FProperties%2F863300109): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [position](position.html) | [jvm]<br>abstract val [position](position.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |


## Inheritors


| Name |
|---|
| [GenericSeekableLittleEndianAccessor](../-generic-seekable-little-endian-accessor/index.html) |

