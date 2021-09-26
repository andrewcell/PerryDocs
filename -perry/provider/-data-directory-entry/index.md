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
| [checksum](index.html#-2074193768%2FProperties%2F863300109) | [jvm]<br>abstract val [checksum](index.html#-2074193768%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [files](files.html) | [jvm]<br>abstract val [files](files.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[DataFileEntry](../-data-file-entry/index.html)> |
| [name](index.html#-590814640%2FProperties%2F863300109) | [jvm]<br>abstract override val [name](index.html#-590814640%2FProperties%2F863300109): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [offset](index.html#2070944200%2FProperties%2F863300109) | [jvm]<br>abstract val [offset](index.html#2070944200%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [parent](index.html#1428385169%2FProperties%2F863300109) | [jvm]<br>abstract val [parent](index.html#1428385169%2FProperties%2F863300109): [DataEntity](../-data-entity/index.html)? |
| [size](index.html#452881818%2FProperties%2F863300109) | [jvm]<br>abstract val [size](index.html#452881818%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [subDirectories](sub-directories.html) | [jvm]<br>abstract val [subDirectories](sub-directories.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[DataDirectoryEntry](index.html)> |


## Inheritors


| Name |
|---|
| [WZDirectoryEntry](../../provider.wz/-w-z-directory-entry/index.html) |

