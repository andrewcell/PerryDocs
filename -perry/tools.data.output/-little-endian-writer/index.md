---
title: LittleEndianWriter
---
//[Perry](../../../index.html)/[tools.data.output](../index.html)/[LittleEndianWriter](index.html)



# LittleEndianWriter



[jvm]\
interface [LittleEndianWriter](index.html)



## Functions


| Name | Summary |
|---|---|
| [skip](skip.html) | [jvm]<br>abstract fun [skip](skip.html)(b: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [write](write.html) | [jvm]<br>abstract fun [write](write.html)(b: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html))<br>Write a byte to the sequence.<br>[jvm]<br>abstract fun [write](write.html)(b: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html))<br>Write an array of bytes to the sequence.<br>[jvm]<br>abstract fun [write](write.html)(b: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Write a byte in integer form to the sequence. |
| [writeASCIIString](write-a-s-c-i-i-string.html) | [jvm]<br>abstract fun [writeASCIIString](write-a-s-c-i-i-string.html)(s: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Writes an ASCII string the sequence.<br>[jvm]<br>abstract fun [writeASCIIString](write-a-s-c-i-i-string.html)(s: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [writeBool](write-bool.html) | [jvm]<br>abstract fun [writeBool](write-bool.html)(b: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Writes a boolean true ? |
| [writeGameASCIIString](write-game-a-s-c-i-i-string.html) | [jvm]<br>abstract fun [writeGameASCIIString](write-game-a-s-c-i-i-string.html)(s: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Writes a maple-convention ASCII string to the sequence. |
| [writeInt](write-int.html) | [jvm]<br>abstract fun [writeInt](write-int.html)(i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Writes an integer to the sequence. |
| [writeLong](write-long.html) | [jvm]<br>abstract fun [writeLong](write-long.html)(l: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>Write a long integer to the sequence. |
| [writeNullTerminatedASCIIString](write-null-terminated-a-s-c-i-i-string.html) | [jvm]<br>abstract fun [writeNullTerminatedASCIIString](write-null-terminated-a-s-c-i-i-string.html)(s: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Writes a null-terminated ASCII string to the sequence. |
| [writePos](write-pos.html) | [jvm]<br>abstract fun [writePos](write-pos.html)(s: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>Writes a 2D 4 byte position information |
| [writeShort](write-short.html) | [jvm]<br>abstract fun [writeShort](write-short.html)(s: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Write a short integer to the sequence. |


## Inheritors


| Name |
|---|
| [GenericLittleEndianWriter](../-generic-little-endian-writer/index.html) |

