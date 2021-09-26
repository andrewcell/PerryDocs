---
title: tools.data.input
---
//[Perry](../../index.html)/[tools.data.input](index.html)



# Package tools.data.input



## Types


| Name | Summary |
|---|---|
| [ByteArrayByteStream](-byte-array-byte-stream/index.html) | [jvm]<br>class [ByteArrayByteStream](-byte-array-byte-stream/index.html)(**array**: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)) : [SeekableInputStreamByteStream](-seekable-input-stream-byte-stream/index.html) |
| [ByteInputStream](-byte-input-stream/index.html) | [jvm]<br>interface [ByteInputStream](-byte-input-stream/index.html)<br>Represents on abstract stream of bytes. |
| [GenericLittleEndianAccessor](-generic-little-endian-accessor/index.html) | [jvm]<br>open class [GenericLittleEndianAccessor](-generic-little-endian-accessor/index.html)(**bs**: [ByteInputStream](-byte-input-stream/index.html)) : [LittleEndianAccessor](-little-endian-accessor/index.html)<br>Provides a generic interface to a Little Endian stream of bytes. |
| [GenericSeekableLittleEndianAccessor](-generic-seekable-little-endian-accessor/index.html) | [jvm]<br>class [GenericSeekableLittleEndianAccessor](-generic-seekable-little-endian-accessor/index.html)(**bs**: [SeekableInputStreamByteStream](-seekable-input-stream-byte-stream/index.html)) : [GenericLittleEndianAccessor](-generic-little-endian-accessor/index.html), [SeekableLittleEndianAccessor](-seekable-little-endian-accessor/index.html)<br>Provides an abstract accessor to a generic Little Endian byte stream. |
| [InputStreamByteStream](-input-stream-byte-stream/index.html) | [jvm]<br>class [InputStreamByteStream](-input-stream-byte-stream/index.html)(**stream**: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html)) : [ByteInputStream](-byte-input-stream/index.html)<br>Provides an abstract wrapper to a stream of bytes. |
| [LittleEndianAccessor](-little-endian-accessor/index.html) | [jvm]<br>interface [LittleEndianAccessor](-little-endian-accessor/index.html) |
| [RandomAccessByteStream](-random-access-byte-stream/index.html) | [jvm]<br>class [RandomAccessByteStream](-random-access-byte-stream/index.html)(**raf**: [RandomAccessFile](https://docs.oracle.com/javase/8/docs/api/java/io/RandomAccessFile.html)) : [SeekableInputStreamByteStream](-seekable-input-stream-byte-stream/index.html)<br>Provides an abstract layer to a byte stream. |
| [SeekableInputStreamByteStream](-seekable-input-stream-byte-stream/index.html) | [jvm]<br>interface [SeekableInputStreamByteStream](-seekable-input-stream-byte-stream/index.html) : [ByteInputStream](-byte-input-stream/index.html)<br>Provides an abstract interface to a stream of bytes. |
| [SeekableLittleEndianAccessor](-seekable-little-endian-accessor/index.html) | [jvm]<br>interface [SeekableLittleEndianAccessor](-seekable-little-endian-accessor/index.html) : [LittleEndianAccessor](-little-endian-accessor/index.html) |

