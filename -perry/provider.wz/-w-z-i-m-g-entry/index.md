---
title: WZIMGEntry
---
//[Perry](../../../index.html)/[provider.wz](../index.html)/[WZIMGEntry](index.html)



# WZIMGEntry



[jvm]\
class [WZIMGEntry](index.html)(parent: [DataEntity](../../provider/-data-entity/index.html), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [DataType](../-data-type/index.html)) : [Data](../../provider/-data/index.html)



## Functions


| Name | Summary |
|---|---|
| [addChild](add-child.html) | [jvm]<br>fun [addChild](add-child.html)(entry: [WZIMGEntry](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../-x-m-l-dom-data/index.html#1183192644%2FFunctions%2F863300109) | [jvm]<br>open fun [forEach](../-x-m-l-dom-data/index.html#1183192644%2FFunctions%2F863300109)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)&lt;in [Data](../../provider/-data/index.html)&gt;) |
| [getChildByPath](get-child-by-path.html) | [jvm]<br>open override fun [getChildByPath](get-child-by-path.html)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Data](../../provider/-data/index.html)? |
| [iterator](iterator.html) | [jvm]<br>open operator override fun [iterator](iterator.html)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)&lt;[Data](../../provider/-data/index.html)&gt; |
| [spliterator](../-x-m-l-dom-data/index.html#-1387152138%2FFunctions%2F863300109) | [jvm]<br>open fun [spliterator](../-x-m-l-dom-data/index.html#-1387152138%2FFunctions%2F863300109)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)&lt;[Data](../../provider/-data/index.html)&gt; |


## Properties


| Name | Summary |
|---|---|
| [children](children.html) | [jvm]<br>open override val [children](children.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Data](../../provider/-data/index.html)&gt; |
| [data](data.html) | [jvm]<br>open override var [data](data.html): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)? = null |
| [name](name.html) | [jvm]<br>open override var [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [parent](parent.html) | [jvm]<br>open override val [parent](parent.html): [DataEntity](../../provider/-data-entity/index.html) |
| [type](type.html) | [jvm]<br>open override var [type](type.html): [DataType](../-data-type/index.html) |

