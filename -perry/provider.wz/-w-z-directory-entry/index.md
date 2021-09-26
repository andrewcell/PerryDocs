---
title: WZDirectoryEntry
---
//[Perry](../../../index.html)/[provider.wz](../index.html)/[WZDirectoryEntry](index.html)



# WZDirectoryEntry



[jvm]\
class [WZDirectoryEntry](index.html) : [WZEntry](../-w-z-entry/index.html), [DataDirectoryEntry](../../provider/-data-directory-entry/index.html)



## Constructors


| | |
|---|---|
| [WZDirectoryEntry](-w-z-directory-entry.html) | [jvm]<br>fun [WZDirectoryEntry](-w-z-directory-entry.html)() |
| [WZDirectoryEntry](-w-z-directory-entry.html) | [jvm]<br>fun [WZDirectoryEntry](-w-z-directory-entry.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), checksum: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), parent: [DataEntity](../../provider/-data-entity/index.html)?) |


## Functions


| Name | Summary |
|---|---|
| [addDirectory](add-directory.html) | [jvm]<br>fun [addDirectory](add-directory.html)(dir: [DataDirectoryEntry](../../provider/-data-directory-entry/index.html)) |
| [addFile](add-file.html) | [jvm]<br>fun [addFile](add-file.html)(fileEntry: [DataFileEntry](../../provider/-data-file-entry/index.html)) |
| [getEntry](get-entry.html) | [jvm]<br>open override fun [getEntry](get-entry.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [DataEntry](../../provider/-data-entry/index.html)? |


## Properties


| Name | Summary |
|---|---|
| [checksum](../-w-z-entry/checksum.html) | [jvm]<br>open override val [checksum](../-w-z-entry/checksum.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [entries](entries.html) | [jvm]<br>val [entries](entries.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [DataEntry](../../provider/-data-entry/index.html)&gt; |
| [files](files.html) | [jvm]<br>open override val [files](files.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[DataFileEntry](../../provider/-data-file-entry/index.html)&gt; |
| [name](../-w-z-entry/name.html) | [jvm]<br>open override val [name](../-w-z-entry/name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [offset](../-w-z-entry/offset.html) | [jvm]<br>open override var [offset](../-w-z-entry/offset.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [parent](../-w-z-entry/parent.html) | [jvm]<br>open override val [parent](../-w-z-entry/parent.html): [DataEntity](../../provider/-data-entity/index.html)? |
| [size](../-w-z-entry/size.html) | [jvm]<br>open override val [size](../-w-z-entry/size.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [subDirectories](sub-directories.html) | [jvm]<br>open override val [subDirectories](sub-directories.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[DataDirectoryEntry](../../provider/-data-directory-entry/index.html)&gt; |

