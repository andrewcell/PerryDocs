---
title: DataDirectoryEntry
---
//[Perry](../../../index.html)/[provider](../index.html)/[DataDirectoryEntry](index.html)



# DataDirectoryEntry



[jvm]\
interface [DataDirectoryEntry](index.html) : [DataEntry](../-data-entry/index.html)



## Functions


| Name | Summary |
|---|---|
| [getEntry](get-entry.html) | [jvm]<br>abstract fun [getEntry](get-entry.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [DataEntry](../-data-entry/index.html)? |


## Properties


| Name | Summary |
|---|---|
| [checksum](../-data-entry/checksum.html) | [jvm]<br>abstract val [checksum](../-data-entry/checksum.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [files](files.html) | [jvm]<br>abstract val [files](files.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[DataFileEntry](../-data-file-entry/index.html)&gt; |
| [name](../-data-entry/name.html) | [jvm]<br>abstract override val [name](../-data-entry/name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [offset](../-data-entry/offset.html) | [jvm]<br>abstract val [offset](../-data-entry/offset.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [parent](../-data-entity/parent.html) | [jvm]<br>abstract val [parent](../-data-entity/parent.html): [DataEntity](../-data-entity/index.html)? |
| [size](../-data-entry/size.html) | [jvm]<br>abstract val [size](../-data-entry/size.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [subDirectories](sub-directories.html) | [jvm]<br>abstract val [subDirectories](sub-directories.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[DataDirectoryEntry](index.html)&gt; |


## Inheritors


| Name |
|---|
| [WZDirectoryEntry](../../provider.wz/-w-z-directory-entry/index.html) |

