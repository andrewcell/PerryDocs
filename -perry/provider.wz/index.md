---
title: provider.wz
---
//[Perry](../../index.html)/[provider.wz](index.html)



# Package provider.wz



## Types


| Name | Summary |
|---|---|
| [DataType](-data-type/index.html) | [jvm]<br>enum [DataType](-data-type/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[DataType](-data-type/index.html)> |
| [FileStoredPngCanvas](-file-stored-png-canvas/index.html) | [jvm]<br>class [FileStoredPngCanvas](-file-stored-png-canvas/index.html)(**width**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **height**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **file**: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)) : [Canvas](../provider/-canvas/index.html) |
| [ImgSound](-img-sound/index.html) | [jvm]<br>data class [ImgSound](-img-sound/index.html)(**dataLength**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **offset**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [ListWZFile](-list-w-z-file/index.html) | [jvm]<br>class [ListWZFile](-list-w-z-file/index.html)(**listWz**: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)) |
| [PNGCanvas](-p-n-g-canvas/index.html) | [jvm]<br>class [PNGCanvas](-p-n-g-canvas/index.html)(**width**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **height**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **dataLength**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **format**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **data**: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)?) : [Canvas](../provider/-canvas/index.html) |
| [WZDirectoryEntry](-w-z-directory-entry/index.html) | [jvm]<br>class [WZDirectoryEntry](-w-z-directory-entry/index.html) : [WZEntry](-w-z-entry/index.html), [DataDirectoryEntry](../provider/-data-directory-entry/index.html) |
| [WZEntry](-w-z-entry/index.html) | [jvm]<br>open class [WZEntry](-w-z-entry/index.html)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **size**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **checksum**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **parent**: [DataEntity](../provider/-data-entity/index.html)?) : [DataEntry](../provider/-data-entry/index.html) |
| [WZFile](-w-z-file/index.html) | [jvm]<br>class [WZFile](-w-z-file/index.html)(**wzFile**: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html), **provideImages**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [DataProvider](../provider/-data-provider/index.html) |
| [WZFileEntry](-w-z-file-entry/index.html) | [jvm]<br>class [WZFileEntry](-w-z-file-entry/index.html)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **size**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **checksum**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **parent**: [DataEntity](../provider/-data-entity/index.html)) : [WZEntry](-w-z-entry/index.html), [DataFileEntry](../provider/-data-file-entry/index.html) |
| [WZIMGEntry](-w-z-i-m-g-entry/index.html) | [jvm]<br>class [WZIMGEntry](-w-z-i-m-g-entry/index.html)(**parent**: [DataEntity](../provider/-data-entity/index.html), **name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **type**: [DataType](-data-type/index.html)) : [Data](../provider/-data/index.html) |
| [WZIMGFile](-w-z-i-m-g-file/index.html) | [jvm]<br>class [WZIMGFile](-w-z-i-m-g-file/index.html)(**wzFile**: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html), **file**: [WZFileEntry](-w-z-file-entry/index.html), **provideImages**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **modernImg**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [WZTool](-w-z-tool/index.html) | [jvm]<br>class [WZTool](-w-z-tool/index.html) |
| [XMLDomData](-x-m-l-dom-data/index.html) | [jvm]<br>class [XMLDomData](-x-m-l-dom-data/index.html) : [Data](../provider/-data/index.html) |
| [XMLWZFile](-x-m-l-w-z-file/index.html) | [jvm]<br>class [XMLWZFile](-x-m-l-w-z-file/index.html)(**rootFile**: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)) : [DataProvider](../provider/-data-provider/index.html) |

