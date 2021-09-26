---
title: Data
---
//[Perry](../../../index.html)/[provider](../index.html)/[Data](index.html)



# Data



[jvm]\
interface [Data](index.html) : [DataEntity](../-data-entity/index.html), [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)&lt;[Data](index.html)&gt;



## Functions


| Name | Summary |
|---|---|
| [forEach](../../provider.wz/-x-m-l-dom-data/index.html#1183192644%2FFunctions%2F863300109) | [jvm]<br>open fun [forEach](../../provider.wz/-x-m-l-dom-data/index.html#1183192644%2FFunctions%2F863300109)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)&lt;in [Data](index.html)&gt;) |
| [getChildByPath](get-child-by-path.html) | [jvm]<br>abstract fun [getChildByPath](get-child-by-path.html)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Data](index.html)? |
| [iterator](index.html#-858216167%2FFunctions%2F863300109) | [jvm]<br>abstract operator fun [iterator](index.html#-858216167%2FFunctions%2F863300109)(): [Iterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)&lt;[Data](index.html)&gt; |
| [spliterator](../../provider.wz/-x-m-l-dom-data/index.html#-1387152138%2FFunctions%2F863300109) | [jvm]<br>open fun [spliterator](../../provider.wz/-x-m-l-dom-data/index.html#-1387152138%2FFunctions%2F863300109)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)&lt;[Data](index.html)&gt; |


## Properties


| Name | Summary |
|---|---|
| [children](children.html) | [jvm]<br>abstract val [children](children.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Data](index.html)&gt; |
| [data](data.html) | [jvm]<br>abstract val [data](data.html): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)? |
| [name](name.html) | [jvm]<br>abstract override val [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [parent](../-data-entity/parent.html) | [jvm]<br>abstract val [parent](../-data-entity/parent.html): [DataEntity](../-data-entity/index.html)? |
| [type](type.html) | [jvm]<br>abstract val [type](type.html): [DataType](../../provider.wz/-data-type/index.html) |


## Inheritors


| Name |
|---|
| [WZIMGEntry](../../provider.wz/-w-z-i-m-g-entry/index.html) |
| [XMLDomData](../../provider.wz/-x-m-l-dom-data/index.html) |

