---
title: WZIMGFile
---
//[Perry](../../../index.html)/[provider.wz](../index.html)/[WZIMGFile](index.html)



# WZIMGFile



[jvm]\
class [WZIMGFile](index.html)(wzFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html), file: [WZFileEntry](../-w-z-file-entry/index.html), provideImages: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), modernImg: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))



## Functions


| Name | Summary |
|---|---|
| [dumpImg](dump-img.html) | [jvm]<br>fun [dumpImg](dump-img.html)(out: [OutputStream](https://docs.oracle.com/javase/8/docs/api/java/io/OutputStream.html), slea: [SeekableLittleEndianAccessor](../../tools.data.input/-seekable-little-endian-accessor/index.html)) |
| [parseExtended](parse-extended.html) | [jvm]<br>fun [parseExtended](parse-extended.html)(entry: [WZIMGEntry](../-w-z-i-m-g-entry/index.html), slea: [SeekableLittleEndianAccessor](../../tools.data.input/-seekable-little-endian-accessor/index.html), endOfExtendedBlock: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [file](file.html) | [jvm]<br>val [file](file.html): [WZFileEntry](../-w-z-file-entry/index.html) |
| [modernImg](modern-img.html) | [jvm]<br>val [modernImg](modern-img.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [provideImages](provide-images.html) | [jvm]<br>val [provideImages](provide-images.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [root](root.html) | [jvm]<br>val [root](root.html): [WZIMGEntry](../-w-z-i-m-g-entry/index.html)? |

