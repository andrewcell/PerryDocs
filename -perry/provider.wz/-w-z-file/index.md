---
title: WZFile
---
//[Perry](../../../index.html)/[provider.wz](../index.html)/[WZFile](index.html)



# WZFile



[jvm]\
class [WZFile](index.html)(wzFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html), provideImages: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [DataProvider](../../provider/-data-provider/index.html)



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [getData](get-data.html) | [jvm]<br>@[Synchronized](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-synchronized/index.html)<br>open override fun [getData](get-data.html)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Data](../../provider/-data/index.html)? |
| [load](load.html) | [jvm]<br>fun [load](load.html)() |


## Properties


| Name | Summary |
|---|---|
| [root](root.html) | [jvm]<br>open override val [root](root.html): [WZDirectoryEntry](../-w-z-directory-entry/index.html) |
| [slea](slea.html) | [jvm]<br>val [slea](slea.html): [SeekableLittleEndianAccessor](../../tools.data.input/-seekable-little-endian-accessor/index.html) |

