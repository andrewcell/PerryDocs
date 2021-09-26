---
title: XMLDomData
---
//[Perry](../../../index.html)/[provider.wz](../index.html)/[XMLDomData](index.html)



# XMLDomData



[jvm]\
class [XMLDomData](index.html) : [Data](../../provider/-data/index.html)



## Constructors


| | |
|---|---|
| [XMLDomData](-x-m-l-dom-data.html) | [jvm]<br>fun [XMLDomData](-x-m-l-dom-data.html)(fis: [FileInputStream](https://docs.oracle.com/javase/8/docs/api/java/io/FileInputStream.html), imageDataDir: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)) |
| [XMLDomData](-x-m-l-dom-data.html) | [jvm]<br>fun [XMLDomData](-x-m-l-dom-data.html)(node: [Node](https://kotlinlang.org/api/latest/jvm/stdlib/org.w3c.dom/-node/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [forEach](index.html#1183192644%2FFunctions%2F863300109) | [jvm]<br>open fun [forEach](index.html#1183192644%2FFunctions%2F863300109)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Data](../../provider/-data/index.html)>) |
| [getChildByPath](get-child-by-path.html) | [jvm]<br>open override fun [getChildByPath](get-child-by-path.html)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Data](../../provider/-data/index.html)? |
| [iterator](iterator.html) | [jvm]<br>open operator override fun [iterator](iterator.html)(): [Iterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)<[Data](../../provider/-data/index.html)> |
| [spliterator](index.html#-1387152138%2FFunctions%2F863300109) | [jvm]<br>open fun [spliterator](index.html#-1387152138%2FFunctions%2F863300109)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Data](../../provider/-data/index.html)> |


## Properties


| Name | Summary |
|---|---|
| [children](children.html) | [jvm]<br>open override val [children](children.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Data](../../provider/-data/index.html)> |
| [data](data.html) | [jvm]<br>open override val [data](data.html): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)? |
| [name](name.html) | [jvm]<br>open override val [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [parent](parent.html) | [jvm]<br>open override val [parent](parent.html): [DataEntity](../../provider/-data-entity/index.html)? |
| [type](type.html) | [jvm]<br>open override val [type](type.html): [DataType](../-data-type/index.html) |

